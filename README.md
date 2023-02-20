
# Neural Machine Translation

This is a PyTorch implementation of a sequence-to-sequence model for Neural Machine Translation (NMT). The model is trained to translate German sentences to English sentences.

The model consists of an encoder and a decoder. The encoder processes the input sequence and generates a context vector, which is passed to the decoder. The decoder then generates the output sequence word-by-word, conditioned on the input sequence and the previous words in the output sequence.

## Requisites

To run this project, you will need the following:

- Python 3.6 or later
- PyTorch 1.8 or later
- torchtext 0.9 or later
- spacy 3.0 or later

## Conclusion

In this project, we implemented a sequence-to-sequence model for Neural Machine Translation using PyTorch. We trained the model to translate German sentences to English sentences and evaluated its performance on a test set. The model achieved a good accuracy and was able to translate sentences that were not in the training set.

## References

- Sutskever, Ilya, Oriol Vinyals, and Quoc V. Le. "Sequence to sequence learning with neural networks." Advances in neural information processing systems. 2014.
- Cho, Kyunghyun, et al. "Learning phrase representations using RNN encoder-decoder for statistical machine translation." arXiv preprint arXiv:1406.1078 (2014).
- PyTorch documentation: https://pytorch.org/docs/stable/index.html
- torchtext documentation: https://torchtext.readthedocs.io/en/latest/index.html
