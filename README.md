# Colaboratory notebooks

- *FSPD_transformer.ipynb*: using a custom transformer architecture to classify food policies by their description (see paper [linktbd])
  Own tokenization and embedding layers within the model. 2-headed attention. *75% accuracy* on test set.
  
- "FSPD_MLP.ipynb" : using a MLP to classify food policies by their description.(see paper [linktbd])
  Tokenizer & embeddings: distilbert-base-uncased. *~90% accuracy* on test set.
   
- "FSPD_lgb.ipynb" : using a lightgbm to classify food policies by their description.(see paper [linktbd])
  Tokenizer & embeddings: distilbert-base-uncased. *~95% accuracy* on test set.
  
- *Gensim_Lovecraft.ipynb*: playing around with Lovecraft's corpus using Gensim and Word2Vec.
