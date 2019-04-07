# Attention based end-to-end frameworks for ASR


## RNN/LSTM
* Basics

    * [M. Schuster and K. K. Paliwal, “Bidirectional Recurrent Neural Networks,” 1997.](https://pdfs.semanticscholar.org/4b80/89bc9b49f84de43acc2eb8900035f7d492b2.pdf)
    * [A. Graves and J. Schmidhuber, “Framewise phoneme classification with bidirectional LSTM and other neural network architectures,” Neural Networks, vol. 18, no. 5–6, pp. 602–610, Jul. 2005.ftp://ftp.idsia.ch/pub/juergen/nn_2005.pdf]
    * [A. Graves, S. Fernández, and J. Schmidhuber, “Bidirectional LSTM networks for improved phoneme classification and recognition,” Int. Conf. Artif. Neural Networks, pp. 799–804, 2005.ftp://ftp.idsia.ch/pub/juergen/icann2005graves.pdf]


## CTC

* Encoder-Decoder

    * [I. Sutskever Google, O. Vinyals Google, and Q. V Le Google, “Sequence to Sequence Learning with Neural Networks.”](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks)
    * [A. Graves, “Sequence Transduction with Recurrent Neural Networks,” Nov. 2012.](https://arxiv.org/abs/1211.3711)
    * [A. Graves, A. Mohamed and G. Hinton, "Speech recognition with deep recurrent neural networks," 2013 IEEE International Conference on Acoustics, Speech and Signal Processing, Vancouver, BC, 2013, pp. 6645-6649.](https://ieeexplore.ieee.org/abstract/document/6638947)
    * [A. Graves and N. Jaitly, “Towards End-To-End Speech Recognition with Recurrent Neural Networks.” pp. 1764–1772, 27-Jan-2014.](http://proceedings.mlr.press/v32/graves14.pdf)




## Attention

* Non-speech papers

    * [A. Graves(https://ieeexplore.ieee.org/document/8068205), “Generating Sequences With Recurrent Neural Networks,” Aug. 2013.](https://arxiv.org/abs/1308.0850)
    * [D. Bahdanau, K. Cho, and Y. Bengio, “Neural Machine Translation by Jointly Learning to Align and Translate,” Sep. 2014.](https://arxiv.org/abs/1409.0473)
    * [K. Xu et al., “Show, Attend and Tell: Neural Image Caption Generation with Visual Attention,” Feb. 2015.](https://arxiv.org/abs/1502.03044)
    * [O. Vinyals, M. Fortunato, and N. Jaitly, “Pointer Networks,” Jun. 2015.](https://arxiv.org/abs/1506.03134)
    * [A. Vaswani et al., “Attention Is All You Need,” Jun. 2017.](https://arxiv.org/abs/1706.03762)
    * [A. See, P. J. Liu, and C. D. Manning, “Get To The Point: Summarization with Pointer-Generator Networks,” Apr. 2017.](https://arxiv.org/abs/1704.04368)
    * [A. Galassi, M. Lippi, and P. Torroni, “Attention, please! A Critical Review of Neural Attention Models in Natural Language Processing,” Feb. 2019.](https://arxiv.org/abs/1902.02181)


* Attention in ASR
    * [J. Chorowski, D. Bahdanau, K. Cho, and Y. Bengio, “End-to-end Continuous Speech Recognition using Attention-based Recurrent NN: First Results,” Dec. 2014.](https://arxiv.org/abs/1412.1602)
    * [J. Chorowski, D. Bahdanau, D. Serdyuk, K. Cho, and Y. Bengio, “Attention-Based Models for Speech Recognition,” Jun. 2015.](https://arxiv.org/abs/1506.07503)
    * [T. ; Hori, S. ; Watanabe, J. R. Hershey, T. Hori, S. Watanabe, and J. R. Hershey, “Joint CTC/attention decoding for end-to-end speech recognition,” 2017.](https://ieeexplore.ieee.org/document/8068205)
    * [Dong, Linhao & Xu, Shuang & Xu, Bo. (2018). Speech-Transformer: A No-Recurrence Sequence-to-Sequence Model for Speech Recognition. 5884-5888. 10.1109/ICASSP.2018.8462506. ](https://www.researchgate.net/publication/327805330_Speech-Transformer_A_No-Recurrence_Sequence-to-Sequence_Model_for_Speech_Recognition)
    * [R. Prabhavalkar, K. Rao, T. N. Sainath, B. Li, L. Johnson, and N. Jaitly, “A Comparison of Sequence-to-Sequence Models for Speech Recognition,” 2017.](https://ai.google/research/pubs/pub46169)
    * [S. Kim, M. L. Seltzer, J. Li, and R. Zhao, “Improved training for online end-to-end speech recognition systems,” in Interspeech 2018, 2018, no. September, pp. 2913–2917.](https://arxiv.org/pdf/1805.03294.pdf)
    * [S. Kim, M. L. Seltzer, J. Li, and R. Zhao, “Improved training for online end-to-end speech recognition systems,” in Interspeech 2018, 2018, no. September, pp. 2913–2917.](https://arxiv.org/abs/1805.03294)
    * [R. Li, X. Wang, H. Mallidi, T. Hori, S. Watanabe, and H. Hermansky, “MULTI-ENCODER MULTI-RESOLUTION FRAMEWORK FOR END-TO-END SPEECH RECOGNITION.”](https://arxiv.org/abs/1811.04897)
    * [T. Hayashi, S. Watanabe, T. Toda, and K. Takeda, “Multi-Head Decoder for End-to-End Speech Recognition,” in Interspeech 2018, 2018, no. September, pp. 801–805.](https://arxiv.org/abs/1804.08050)

* ESPnet references
    1. Dot product attention - [M.-T. Luong, H. Pham, and C. D. Manning, “Effective Approaches to Attention-based Neural Machine Translation,” Aug. 2015.](https://arxiv.org/abs/1508.04025)
    2. Additive attention  - [D. Bahdanau, K. Cho, and Y. Bengio, “Neural Machine Translation by Jointly Learning to Align and Translate,” Sep. 2014.](https://arxiv.org/abs/1409.0473)
    3. Location aware attention - [J. Chorowski, D. Bahdanau, D. Serdyuk, K. Cho, and Y. Bengio, “Attention-Based Models for Speech Recognition,” Jun. 2015.](https://arxiv.org/abs/1506.07503)
    4. 2D Location aware attention - [J. Chorowski, D. Bahdanau, D. Serdyuk, K. Cho, and Y. Bengio, “Attention-Based Models for Speech Recognition,” Jun. 2015.](https://arxiv.org/abs/1506.07503)
    5. Location aware recurrent attention - [J. Chorowski, D. Bahdanau, D. Serdyuk, K. Cho, and Y. Bengio, “Attention-Based Models for Speech Recognition,” Jun. 2015.](https://arxiv.org/abs/1506.07503)
    6. Coverage mechanism attention - [A. See, P. J. Liu, and C. D. Manning, “Get To The Point: Summarization with Pointer-Generator Networks,” Apr. 2017.](https://arxiv.org/abs/1704.04368)
    7. Coverage mechanism location aware attention - [A. See, P. J. Liu, and C. D. Manning, “Get To The Point: Summarization with Pointer-Generator Networks,” Apr. 2017.](https://arxiv.org/abs/1704.04368)
    8. Multi head dot product attention - [A. Vaswani et al., “Attention Is All You Need,” Jun. 2017.](https://arxiv.org/abs/1706.03762)
    9. Multi head additive attention - [A. Vaswani et al., “Attention Is All You Need,” Jun. 2017.](https://arxiv.org/abs/1706.03762)
    10. Multi head location based attention - [A. Vaswani et al., “Attention Is All You Need,” Jun. 2017.](https://arxiv.org/abs/1706.03762)
    11. Multi head location based attention - [A. Vaswani et al., “Attention Is All You Need,” Jun. 2017.](https://arxiv.org/abs/1706.03762)
    12. Multi head multi resolution location based - - [A. Vaswani et al., “Attention Is All You Need,” Jun. 2017.](https://arxiv.org/abs/1706.03762)