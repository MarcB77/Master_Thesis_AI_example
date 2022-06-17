# Master_Thesis_AI_example
This is a working example, as a Jupyter notebook in vscode.

Make sure to install the following packages:

pip install torch
pip install click==8.0.4
pip install keras
pip instal tensorflow
pip install spacy 
pip install scispacy
pip install nltk 
pip install pyspark
pip install pandas
pip install numpy
pip install scikit-learn
pip install tqdm
pip install collection
pip install seaborn


Important to locally download the spacy packages:
python -m spacy download en_core_web_lg
python -m spacy download nl_core_news_lg

Follow the following steps to make a model on your own, and test with the provided data.
Important to mention, is that the dataset is very small. Since this company did not allowed to use all the available data.

Steps:
1. Run NLP_.ipynb (This will create a .pkl file were a preprocessed dataframe will be stored.)
2. Run Train_Multi_Single.ipynb (This notebook will train and test your model based on a small dataset of 600 samples. -> 300 True and 300 False classes).


