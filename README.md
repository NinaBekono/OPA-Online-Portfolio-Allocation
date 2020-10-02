# API

sur le conda prompt : 
pip install pandas_datareader


sur le jupyter notebook :

import pandas as pd
import pandas_datareader as dr


dr.data.get_data_yahoo ('ibm', start = '2018-09-01', 
                       end = '2018-11-24')

