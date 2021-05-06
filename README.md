# Extracting, exploring, summarizing information from Twitter social media, aggregated news during disasters

## Project Description:  

In this research project, the goal is to extract information from tweets posted on Twitter social media during disasters and provide knowledge extracted to the organizations, charities and in turn, help them take decisions about disaster recovery. Also, the information extraction process can be automated and will be discussed in the future scope of this research work.  On a higher level, this is made possible by the use of powerful Natural Language Processing (NLP) algorithms like BERT and using word embeddings from Word2Vec algorithm.

## Dependencies:

1. Jupyter Notebook, instructions found [here](https://jupyter.org/)
2. Python 3.5 or above
3. scikit-learn
4. nltk
5. pandas
6. numpy
7. textblob
8. seaborn
9. gensim
10. matplotlib

All these packages (3-10) can be installed by using the command 'pip3 install <package_name>'. For example, 'pip3 install numpy' will install numpy

There are 8 '.ipynb' files or Jupyter Notebooks, 1 '.pdf' research report and 4 '.csv' files in this repository. Each .csv file consists of data required for running the notebooks. Notebooks starting with 'crisis_nlp_' consist models built in each disaster type and notebooks starting with 'sklearn_BERT_' consist of BERT model for each disaster type. Running BERT notebooks require GPU, so it is better if you run these files in Google Colab and setting the notebook type to GPU.
