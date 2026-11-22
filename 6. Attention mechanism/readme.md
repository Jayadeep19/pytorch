# In this chapter
1. The first notebook introduces what attention is and how different vectors (query, key, value) contribute to getting a weighted sum over all the input tokens
2. The second notebook introduces 'differentiable indexing', which makes it possible for NN's to learn the query, Key, value vectors.
    - on MNIST dataset, I implemented
    - Hard Indexing
    - Soft indexing using attention
    - Multi Query attention from scratch
    - Multi Head attention from scratch
    - Multi Head attention using pytorch implementation
3. The third notebook **trains a simple MHA** that finds **similar images** in the dataset to the input image. Used dataset is our beloved MNIST hand written digits
