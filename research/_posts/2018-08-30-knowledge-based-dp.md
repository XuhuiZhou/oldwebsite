---
title: Research internship at SUTD
image: /assets/img/blog/sutd.jpg
description: >
  My resaerch internship at Singapore University of Technology and Design.
---

I was fortunate to work with Prof. [Yue Zhang](https://frcchang.github.io/) at Singapore University of Technology and Design (SUTD) this summer. 

Dependency parsing has been proven to be useful for many NLP tasks and the current algorithm has a strong performance in the newswire domain. Still, why does the state of art algorithm sometimes link a head with a dependent in a way that seems absurd to normal people and fails to generalize to other domains? Realizing the importance of knowledge in processing language, I created a knowledge-based (KB) Dependency parser along with a Dependency knowledge base (DKB). Directly injecting knowledge into the Recurrent neural network (RNN) is hard. Borrowing ideas from discrete math, I viewed the sentence and corresponding knowledge as a graph whose nodes are words and edges are dependent relationships. I further modified the Sentence-state LSTM (SLSTM) to an encoder, which can naturally incorporate, process and understand the information in DKB in the training process. 


Presently, we are preparing a paper about this research. Here is the core part of our [code](https://github.com/XuhuiZhou/A_knowledge-based_encoder). I also want to thank [Xuezhe max](https://github.com/XuezheMax/NeuroNLP2) for the nice implementation of the Deep Biaffine Parser in Python and his kind responses regarding my research questions!


I was fortunate to attend the [2018 Singapore Symposium on Natural Language Processing](https://event.statnlp.org/). I was honored to present out group's poster about [Sentence-State LSTM](https://arxiv.org/abs/1805.02474) and communicate with Prof. Vincent Ng, Noah Smith, and so on.




