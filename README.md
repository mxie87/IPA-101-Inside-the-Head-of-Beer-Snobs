**Project Goals**

The goal of this project was to answer the question, "WHAT ARE THE ELEMENTS OF A GREAT IPA?" from the lens of brewers and beer enthusiast, using unsupervised learning techniques and natural language processing (NLP). Data was scrapped from www.beeradvocate.com. Reviews from 300 different IPA beers were scrapped, totaling nearly 55,000 reviews. 

This project involves the use of data scraped from the web, and applying unsupervised learning techniques to discover insights. Specifically, Latent Dirichlet Allocation was used for Topic Modeling. Sentiment Analysis was also performed. A dimensional reduction technique named T-distributed Stochastic Neighbor Embedding (t-SNE) was applied in an attempt to gain meaninful visualization, however, this dataset did not seem to be a good fit for t-SNE. 

---

**Methodology** 
1. Obtain Data (webscrapping using BueatifulSoup)
2. Preprocessing: lowercase, remove punctuations
3. Tokenization
4. Filter with Stop-Words
5. Lemmatization (prior to LDA) 
6. Latent Dirichlet Allocation (LDA) for topic modeling
7. Bigram, Trigram
8. Sentiment Analysis
9. t-SNE for visualization (Not Applicable)

---

NLP Modules/Libraries Used:
* NLTK
* Textblob
* SKlearn
* Gensim
* Spacy
* pyLDAvis (for visualization)
