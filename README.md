# Master_Thesis_AI_example  <br />
This is a working example, as a Jupyter notebook in **vscode**. <br />
Configured Python kernel = 3.7.9 64-bit <br />

The packages that are needed for this project, can be installed by running in your terminal: <br />
**pip install -r requirements.txt** <br />
Or make sure to install the following packages:  <br />

pip install torch             <br />
pip install click==8.0.4      <br />
pip install keras             <br />
pip instal tensorflow         <br />
pip install spacy             <br />
pip install scispacy          <br />
pip install nltk              <br />
pip install pyspark           <br />
pip install pandas            <br />
pip install numpy             <br />
pip install scikit-learn      <br />
pip install tqdm              <br />
pip install collection        <br />
pip install seaborn           <br />
  
<br />
Important to locally download the spacy packages in your terminal: <br />
python -m spacy download en_core_web_lg           <br />
python -m spacy download nl_core_news_lg          <br />

Follow the following steps to make a model on your own, and test with the provided data.  <br />
Important to mention, is that the dataset is very small. Since this company did not allowed to use all the available data.  <br />

Steps:  <br />
1. Run **NLP_.ipynb** (This will create a .pkl file inside folder 'dataset' were a preprocessed dataframe will be stored.)  <br />
2. Run **Train_Multi_Single.ipynb** (This notebook will train and test your model based on a small dataset of 1000 samples. -> 500 True and 500 False classes).  <br />

Make sure you use 'Master_Thesis_AI_example' as working directory.
