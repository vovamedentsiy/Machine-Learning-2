# Machine Learning 2
Programming and homework assignments for the Autumn 2019 Machine Learning 2 course at University of Amsterdam


## Lab assignment 1: Independent Component Analysis
Implented independent component analysis (ICA) to demix 5 audio signals using activation functions:  <img src="https://render.githubusercontent.com/render/math?math=\phi_0(x) = -tanh(x), \phi_1(x) = tanh(x)-x, \phi_2(x) = -x^3, \phi_3(x) = -\frac{6x}{5 %2B x^2}">. 
<p> 
    <img src="https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/lab/imgs/lab1/1.png" width="250" height ="250" />
    <br>
    <em>Real signal</em> 
<p\>
    
<p> 
    <img src="https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/lab/imgs/lab1/2.png" width="200" height ="250" /> <img src="https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/lab/imgs/lab1/3.png" width="200" height ="250" />
    <br>
    <em>Signals reconstructed using demixing matrix and various activation functions</em> 
<p\>

Find the code [here](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/lab/lab1/12179078_lab1.ipynb)


## Lab assignment 2: Inference in graphical models
Implemented sum-product and max-sum algorithms for the medical graph. 

Find the code [here](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/lab/lab2/12179078_lab2.ipynb)

## Lab assignment 3: Variational inference
1. Implemented EM algorithm for the Bernoulli mixture model and trained it on the MNIST data: 

<img src="https://render.githubusercontent.com/render/math?math=p(\bx|\bmu, \bpi) = \sum_{k=1}^K  \pi_k \prod_{i=1}^D \mu_{ki}^{x_i}(1-\mu_{ki})^{(1-x_i)}">

2. Implemented VAE and trained it on the MNIST data
Find the code [here](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/lab/lab3/12179078_lab3.ipynb)



## Homework assignment 1: Common probability distributions

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw1.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW1_medentsiy.pdf)

## Homework assignment 2: Mutual information, entropy and KL-divergence

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw2.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW2_medentsiy.pdf)

## Homework assignment 3: Graphical models (Bayesian networks and Markov network)

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw3.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW3_medentsiy.pdf)

## Homework assignment 4: Sum-product algorithm

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw4.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW4_medentsiy.pdf)

## Homework assignment 5: Expectation maximization

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw5.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW5_medentsiy.pdf)

## Homework assignment 6: Sampling methods, MCMC, Variational EM

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw6.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW6_medentsiy.pdf)

## Homework assignment 7: Linear dynamical systems and Causality 

[Problems](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/task/hw7.pdf) and [solutions](https://github.com/vovamedentsiy/Machine-Learning-2/blob/main/homeworks/hw/ML2_HW7_medentsiy.pdf)
