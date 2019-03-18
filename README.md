# nltk-tutorials
different methods to impliment nltk tools for NLP

# install nltk library using on python virtual environment
pip install nltk

# then check if package is installed then open python shell
 import nltk 
 
 nltk.download()
 
 # download all pakages avialble in nltk
 
 
#NLU ambiquity
 Manily classified in to 3 types
 
  1.Lexical Ambiquity
  
  2.Syntactic Ambiquity
  
  3.Referential Ambiquity
  
  
  # Problem of text classification of positive and negative Reviews

.. code:: python

  
    import numpy as np
    import pandas as pd
    import os
    from sklearn.feature_extraction.text import CountVectorizer 
    print(os.listdir(nltk.data.find('corpora'))) #shows the corpora folder to python files
 
