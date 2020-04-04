# data-science
Deep learning (imbalanced) classification project to match scraped adverts to products.

1) Scrape advert data.
2) Process scraped text to generate clean advert text blocks.
3) Additional processing step to remove all identifying features from adverts text to produce 'chat-set'.
4) Use 'chat-set' to produce Markov models (language specific).
5) Use product data set to create advert templates consisting of advert data interspersed with unique 'chat-text'.
6) Train deep learning neural network (featuring word vector embeddings, 1D convolutions and GlobalMaxPooling for feature selection, and a deep, densely connected forward feed secion for classification).
7) Test the trained netowrk and produce plots to examine optimal predictive cutoffs.

