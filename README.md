# Text-Classification-
Text Classification using Transformer Model
Transformer Model- A transformer architecture consists of an encoder and decoder that work together. The attention mechanism lets transformers encode the meaning of words based on the estimated importance of other words or tokens. This enables transformers to process all words or tokens in parallel for faster performance, helping drive the growth of increasingly bigger LLMs.

For the purpose of classification , we will only use the encoder block of the original transformers model designed for sequence problems.

Multi-Headed Attention

Multi-head Attention is a module for attention mechanisms which runs through an attention mechanism several times in parallel. The independent 
attention outputs are then concatenated and linearly transformed into the expected dimension.

The Self Attention mechanism is used several times in parallel in Multi-Head attention.

Multiple attention heads allows for attending to parts of the sequence differently

During self attention a word's attention score with itself will be the highest, therefore by using mutli-head attention a word can establish its relationship with other words in the sequence by calculating the attention scores with them in parallel.


Results:
Precision: 93%
Recall: 93%

The dataset is attached here itself.

