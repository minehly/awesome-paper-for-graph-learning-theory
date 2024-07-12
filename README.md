# Awesome-paper-for-graph-learning-theory
A collection of awesome papers for graph learning theory.
## Table of Contents

- [awesome-paper-for-graph-learning-theory](#awesome-paper-for-graph-learning-theory-)
  -[Surveys](#surveys)
  - [Expressive power](#expressive-power)
  - [Generalization bound](#generalization-bound)
  - [Optimization](#optimization)
  - [Over-smoothing](#over-smoothing)
  - [Over-squashing](#over-squashing)
    
## Surveys
- Theory of graph neural networks: Representation and learning
- Weisfeiler and leman go machine learning: The story so far
- Over-squashing in graph neural networks: A comprehensive survey

## Expressive power

1. [Fine-grained expressivity of graph neural networks](https://proceedings.neurips.cc/paper_files/paper/2023/file/9200d97ca2bf3a26db7b591844014f00-Paper-Conference.pdf), NeurIPS 2024 \
   *Boker, Jan and Levie, Ron and Huang, Ningyuan and Villar, Soledad and Morris, Christopher*
- Rethinking the expressive power of gnns via graph biconnectivity
- Beyond Weisfeiler-Lehman: A Quantitative Framework for GNN Expressiveness

## Generalization bound

### Complexity of hypothesis space based

1. [The Vapnik–Chervonenkis dimension of graph and recursive neural networks](https://www.sciencedirect.com/science/article/pii/S0893608018302363?via%3Dihub), Neural Networks 2018 \
   *Scarselli, Franco and Tsoi, Ah Chung and Hagenbuchner, Markus*
   
2. [Generalization and Representational Limits of Graph Neural Networks](http://proceedings.mlr.press/v119/garg20c/garg20c.pdf), ICML 2020 \
   *Garg, Vikas and Jegelka, Stefanie and Jaakkola, Tommi*
   
3. [Generalization bounds for graph convolutional neural networks via rademacher complexity](https://arxiv.org/abs/2102.10234), CoRR 2021 \
   *Shaogao Lv*

4. [Optimization and generalization analysis of transduction through gradient boosting and application to multi-scale graph neural networks](https://proceedings.neurips.cc/paper_files/paper/2020/file/dab49080d80c724aad5ebf158d63df41-Paper.pdf), NeurIPS 2020 \
   *Kenta Oono, Taiji Suzuki*

5. [Learning theory can (sometimes) explain generalisation in graph neural networks](https://proceedings.neurips.cc/paper_files/paper/2021/file/e34376937c784505d9b4fcd980c2f1ce-Paper.pdf), NeurIPS 2021 \
   *Pascal Mattia Esser, Leena C. Vankadara, Debarghya Ghoshdastidar*

6. [Graph convolution network based recommender systems: Learning guarantee and item mixture powered strategy](https://proceedings.neurips.cc/paper_files/paper/2022/file/18fd48d9cbbf9a20e434c9d3db6973c5-Paper-Conference.pdf), NeurIPS 2022 \
   *Leyan Deng, Defu Lian, Chenwang Wu, Enhong Chen*

7. [Towards understanding generalization of graph neural networks](https://proceedings.mlr.press/v202/tang23f/tang23f.pdf), ICML 2023 \
   *Huayi Tang, Yong Liu*

### PAC-Bayes based

1. [A pac-bayesian approach to generalization bounds for graph neural networks](https://openreview.net/pdf?id=TR-Nj6nFx42), ICLR 2021 \
   *Renjie Liao, Raquel Urtasun, Richard S. Zemel*

2. [Generalization bounds and size generalization for graph neural networks](https://open.library.ubc.ca/media/download/pdf/24/1.0417272/3), Ph.D. dissertation, University of British Columbia, 2022 \
   *Sales, Emmanuel*

3. [Generalization in graph neural networks: Improved pacbayesian bounds on graph diffusion](https://proceedings.mlr.press/v206/ju23a/ju23a.pdf), AISTATS 2023 \
   *Haotian Ju, Dongyue Li, Aneesh Sharma, Hongyang R. Zhang*

4. [Pac-bayesian adversarially robust generalization bounds for graph neural network](https://arxiv.org/pdf/2402.04038), CoRR 2024 \
   *Tan Sun, Junhong Lin*

### Stability based

1. [Stability and generalization of graph convolutional neural networks](https://dl.acm.org/doi/pdf/10.1145/3292500.3330956), KDD 2019 \
   *Saurabh Verma, Zhi-Li Zhang*

2. [The generalization error of graph convolutional networks may enlarge with more layers](https://www.sciencedirect.com/science/article/pii/S0925231220317367?via%3Dihub), Neurocomputing 2021 \
   *Xianchen Zhou, Hongxia Wang*

3. [On provable benefits of depth in training graph convolutional networks](https://proceedings.neurips.cc/paper_files/paper/2021/file/524265e8b942930fbbe8a5d979d29205-Paper.pdf), NeurIPS 2021 \
   *Weilin Cong, Morteza Ramezani, Mehrdad Mahdavi*

### NTK based

1. [Graph neural tangent kernel: Fusing graph neural networks with graph kernels](https://proceedings.neurips.cc/paper_files/paper/2019/file/663fd3c5144fd10bd5ca6611a9a5b92d-Paper.pdf), NeurIPS 2019 \
   *Simon S. Du, Kangcheng Hou, Ruslan Salakhutdinov, Barnabás Póczos, Ruosong Wang, Keyulu Xu*
   
## Optimization
- Optimization of graph neural networks: Implicit acceleration by skip connections and more depth
- How Graph Neural Networks Learn: Lessons from Training Dynamics in Function Space
- A convergence analysis of gradient descent on graph neural networks

## Over-smoothing
- Deeper insights into graph convolutional networks for semi-supervised learning
- Simple and deep graph convolutional networks
- Graph Neural Networks Exponentially Lose Expressive Power for Node Classification

## Over-squashing
- Understanding over-squashing and bottlenecks on graphs via curvature
- On over-squashing in message passing neural networks: The impact of width, depth, and topology
- Revisiting over-smoothing and over-squashing using ollivier-ricci curvature
