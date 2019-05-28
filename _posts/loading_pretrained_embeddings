---
layout: post
title: 'Loading Pre-trained Embeddings into Keras'
date: 2019-04-01 20:12:55.000000000 -08:00
categories: []
tags: []
status: publish
type: post
published: true
---

Regardless of whether you are using the built-in Keras API or loading your own custom built embedding, you will need to follow two critical steps:

1. Create a word to index mapping
2. Create an embedding matrix that contains the weights for each word

Note that you don't need step 2 when you are training your own embedding layer.

## Keras API
If you are using the Keras API, it can be as easy as running the following code:

`
from load_glove_embeddings import load_glove_embeddings
word2index, embedding_matrix = load_glove_embeddings('data_embeddings/en/glove.6B.50d.txt', embedding_dim=50)
`

## Custom Embeddings


`
from keras.models import Model
from keras.layers import Input

embedding_layer = Embedding(input_dim=embedding_matrix.shape[0],
                            output_dim=embedding_matrix.shape[1], 
                            input_length=maxlen,
                            weights=[embedding_matrix], 
                            trainable=False, 
                            name='embedding_layer')

i = Input(shape=(maxlen,), dtype='int32', name='main_input')
x = embedding_layer(i)
x = Flatten()(x)
o = Dense(1, activation='sigmoid')(x)

model = Model(inputs=i, outputs=o)
`
