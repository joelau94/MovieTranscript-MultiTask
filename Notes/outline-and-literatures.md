# Things to Explore

## 1. Multi-task learning

a. Hyper-param: coefficient of task losses

b. How tasks benefit from each other

### Papers

- [RNN for Text Classification with Multitask Learning](https://www.ijcai.org/Proceedings/16/Papers/408.pdf)
- [A Generalized Recurrent Neural Architecture for Text Classification with Multitask Learning](https://www.ijcai.org/proceedings/2017/0473.pdf)
- [Multiple Instance Learning Networks for Fine-Grained Sentiment Analysis](http://aclweb.org/anthology/Q18-1002)
- [DRAGNN: A Transition-based Framework for Dynamically Connected Neural Networks](https://arxiv.org/pdf/1703.04474.pdf)

## 2. Incorporating document-level context

a. start from sentence level

b. possible mechanisms:

  - Hierarchical structure
  - Gating information flow

### Papers

- [Document-Level Neural Machine Translation with Hierarchical Attention Networks](https://arxiv.org/pdf/1809.01576.pdf)
- [Hierarchical Attention Networks for Document Classification](http://www.aclweb.org/anthology/N16-1174)
- [Document Modeling with Gated Recurrent Neural Network for Sentiment Classification](http://aclweb.org/anthology/D15-1167)

## 3. Structures

### a. encoding structure (low-level to high-level sequence)

  - RNN
  - Transformer [Attention Is All You Need](https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf)

### b. summarizing structure (sequence to vector)

  - Average
  - Last RNN state
  - CNN (multi-channel max-pooling) [Convolutional Neural Networks for Sentence Classification](http://www.aclweb.org/anthology/D14-1181)
  - Attention (query-key-value: query-vector per task) [End-To-End Memory Networks](https://papers.nips.cc/paper/5846-end-to-end-memory-networks.pdf)

## 4. Multi-modality (time permitting)

### Papers

- [Attention-based Multimodal Neural Machine Translation](http://www.aclweb.org/anthology/W16-2360)