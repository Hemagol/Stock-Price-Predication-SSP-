## Requirements 
### Importing necessary library 
* Install Pandas libaray as pip install pandas and import pandas as pd
* Install Joblife libaray as pip install joblife and import joblife
## Usage 
* After importing all libraries, load the Trained Model by 
    "model=joblib.load('Path')"
  paste the Path of downloaded trained model .pkl extension path.
* Predict with real data by giving the real data of the Open, High and Low price of company by following below Dictionary structure.
   "input_data = {'Open': [150.0],'High': [155.0],'Low': [148.0]}"
  Note: Intial letter shoud be in capital of all Features.
* Lastly input data is converted to dataframe by using the pandas. 
   'a=pd.DataFrame(input_data)'
* Finally prdict the with real data and output will be the close price of stock .
   'Predication = mod.predict(a))'
    'print(predication)
