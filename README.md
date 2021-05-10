#### Capstone-606
Based on the categorization of the deep learning models a special attention is given to the attack detection methods which are build on different kinds of architectures such as autoencoders ,recurrent neural networks.
A total of around 1000000 instances were collected and are currently stored in a CSV (Comma Separated Values) file. Link to the dataset :https://drive.google.com/file/d/1HDeyt92iaXASdQ_CsuZbwpSX7yCJEkv0/view?usp=sharing
### Feature_extraction.ipynb: This is the first phase of the project where data preprocessing and feature engineering are being performed. In data preprocessing Pandas DataFrame.fillna() is used to replace Null values in dataframe.Dataset csv file has null values, which are displayed as NaN in Data Frame. Just like pandas dropna() method manage and remove Null values from a data frame, fillna() manages and let the user replace NaN values with some value of their own.The dataset have many inf values as well. The simplest way to handle infinity values would be to first replace them (infs) to NaN.
Tranforming the prediction target label(y).These are transformers that are not intended to be used on features, only on supervised learning targets (class Labels). In other words This transformer should be used to encode target values, i.e. y, and not the input X. We Encode target labels with value between 0 and n_classes-1 using below API
class sklearn.preprocessing.LabelEncoder

