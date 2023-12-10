# English to French Translation

![dataset-cover](https://github.com/raj-pulapakura/English-to-French-Translation/assets/87762282/8f6e931a-da32-40f8-af08-29253aceb3c0)

English to French Machine Translation, using the Encoder-Decoder architecture with Multi-headed Attention.

### Machine Translation

Machine Translation is the process of converting text/speech from one language to another. In this notebook, we tackle specifically translation of English text to French text.

### Encoder-Decoder with Attention

![Encoder-Decoder architecture with Attention - TensorFlow "Neural Machine Translation with Attention" tutorial](https://www.tensorflow.org/images/tutorials/transformer/RNN%2Battention-words-spa.png)

`Encoder-Decoder with Attention` is a well-known architecture for machine translation, although it has become somewhat outdated with the rise of the powerful `Transformer` architecture.

However, it is still a very useful project to work through to get a deeper understanding of sequence-to-sequence models and attention mechanisms (before going on to Transformers).

### Inspiration

This notebook was mainly inspired by TensorFlow's amazing tutorial on [Neural machine translation with attention](https://www.tensorflow.org/text/tutorials/nmt_with_attention), which I have made open source contributions to.

## Table of contents:

Go to `code.ipynb` to view the notebook.

Here is a summary of what will be covered in the notebook:

<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [1. Load Data](#1-load-data)
- [2. Create datasets](#2-create-datasets)
- [3. TextVectorization](#3-textvectorization)
   * [3.1 Prepare vectorizers](#31-prepare-vectorizers)
      + [3.1.1 English Vectorizer](#311-english-vectorizer)
      + [3.1.2 French Vectorizer](#312-french-vectorizer)
      + [3.1.3 Example from dataset](#313-example-from-dataset)
   * [3.2 Create new datasets with word indices](#32-create-new-datasets-with-word-indices)
- [4. Building up the Encoder-Decoder Model](#4-building-up-the-encoder-decoder-model)
   * [4.1 Encoder](#41-encoder)
   * [4.2 Cross-Attention](#42-cross-attention)
   * [4.3 Decoder](#43-decoder)
   * [4.4 Combining Encoder and Decoder into Translator](#44-combining-encoder-and-decoder-into-translator)
- [5. Training](#5-training)
- [6. Inference](#6-inference)
- [7. Conclusion](#7-conclusion)
