# Debiasing-Word-Vectors

In the following notebook, we'll examine gender biases that can be reflected in a word embedding, and explore algorithms for reducing the bias. In addition to learning about the topic of debiasing, this notebook will also help hone your intuition about what word vectors are doing. 

First, see how the GloVe word embeddings relate to gender. We'll begin by computing a vector $g = e_{woman}-e_{man}$, where $e_{woman}$ represents the word vector corresponding to the word *woman*, and $e_{man}$ corresponds to the word vector corresponding to the word *man*. The resulting vector $g$ roughly encodes the concept of "gender". 
