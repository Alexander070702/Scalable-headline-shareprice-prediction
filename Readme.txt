# Stockmarket Prediction with Headlines


## Description: PySpark Notebook Trained Machine Learning Algorithmus...

Predict the influence of a headline on the stockmarket. Through the input of a headline (best results with financial sector) 
the prediction encounters first, which stock is influenced by each headline. Then the headlines goes through a second process,
where it first gets additional attributes and then get predicted on a positive or negative effect for the specific stock.

As further combination for different tools, these trained models could be used to combine them with an RSS-Feed input from an newsportal (e.g. XML),
and on the output side it could perform over a dedicated sever a call through a trading API. (Because of time reasons, we only trained the models :) )
On the prefered time sequence, for example minutes, or days, it could also watch the actual price movement of the prediction and train itself further.


## Directory:

- data/ ..................................................... # The data which is used to train the model
--- shares/ ................................................. # The stock data
----- etfs/ ................................................. # Not yet used
----- stocks/ ............................................... # The real stocks, open and close on each csv
------- ...                                                   # Many stock csvs
----- 'symbols_valid_meta.csv' .............................. # Only for testing phase used, could improve the matching stock names prediction, because of the linking real names.
--- headlines/ .............................................. # The headline data
----- 'raw_analyst_ratings.csv' ............................. # Financial headlines to train the model
----- ...                                                     # Also other file, because to less RAM on the jupyter hub to train the models

- 'Final.ipynb' ............................................. # Combined predictions
- 'Final.html'	............................................. # HTML Version of the Notebook
- 'Readme.txt' .............................................. # Directory description


## Developers:

 - Alexander Hillisch (alexander.hillisch@s.wu.ac.at)
 - Maximilian Priessnitz (maximilian.priessnitz@s.wu.ac.at)
 - Gabriel Zeisz (gabriel.silvius.zeisz@s.wu.ac.at)


## License:

This software is protected by a proprietary license. The source code and all associated rights remain the property of the developers.

**NOTE: Any distribution or sharing of the software with third parties is strictly prohibited.**


## Disclaimer

The software is provided "as is" without any express or implied warranty. The developer shall not be held liable for any damages or losses arising from the use of this software.
The programm is also not yet finished for any useable case. It is only performed on a small amount of data and should be improved to use it on all data.


## Support

For any questions, assistance, or inquiries, please contact us.


