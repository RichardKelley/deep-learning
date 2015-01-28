Week 1 - SVD, LSI, word2vec
======

This week we'll cover singular value decomposition (SVD) as an
alternative to using eigenvalues directly in PCA. We'll talk about how
this is the same thing, and then we'll look at inverted indices for
text corpora. Once we have a handle on inverted indices, we'll look at
using SVD to implement "latent semantic indexing," which is supposed
to give us low-dimensional vector representations of documents and
words. We'll talk about issues with this approach, and then we'll look
at scikit-learn and gensim: two python libraries for doing machine
learning and text analysis.

To run the gensim notebook, you'll need to download the dataset from
here: https://code.google.com/p/word2vec/