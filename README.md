# ML and DL study

Overview and some notes

![Relation_between_Terminology](https://raw.githubusercontent.com/lennox0909/ML_and_DL_basic/master/slides/ML_Relation_between_Terminology.jpg)
Slide from NTU李弘毅老師

**Figure Legend and Description**

## Scenario (depend on kind of data)
* Supervised Learning
* Semi-Supervised Learning
* Unsupervised Learning
* Reinforcement Learning
* Transfer Learning

## Task (depend on kind of question to be adressed)
* Regression
  * Data with numeric size relationship
  * Ex. Age, Price

* Classification
  * Data without numeric size relationship
  * Ex. Color, Mortality

* Structured (structured input/output)
   * Speech Recognition (Voice to Sentense)
   * Translation (Chinese to English)
   * etc.

## Method (mathematic algorithm)
* Linear Model
* Non-Linear Model
  * Deep Learning
  * SVM
  * Decision Tree
  * K-NN
  * etc.

## Talk a little bit more on Learnings
### Supervised Learning
**Input/Output as a pair, require labor labeling**
* Regression: function output as a scala
* Classification:
  * Binary: Yes or No
  * Multi-calss: class 1, 2 ,3 ...etc.

### Semi-Supervised Learning
**Little amount of labeled data, with huge amount of unlabeled data**

### Unsupervised Learning
**Unlabeled data**
* Clustering
* Dimention reduction
* Generation (GAN)
* Word Embedding
* Multi-lingual Embedding
* etc.

### Reinforcement Learning
**Unlabeled data, mostly from the environment in realtime**

## Supervised vs Reinforcement
* Supervised: Learn from teacher (label)
* Reinforcement: Learn from score feedbacked from environment
  * Reward delay issue

## Logistic Regression vs Linear Regression
* Logistic Regression: Cross-entropy as loss function
* Linear Regression: Square-error as loss function
* Cross-entropy has more gradient than Square-error
![Logistic_vs_Linear_Regression](https://raw.githubusercontent.com/lennox0909/ML_and_DL_basic/master/slides/Logistic_vs_Linear_Regression.JPG)
Slide from NTU李弘毅老師

## Mini-batch descent vs Stochastic descent
* **Mini-batch descent** descent can be faster than **Stochastic descent** due to parallel computation
* Very large batch size can yield worse performance
![mini_batch_vs_stochastic_descent](https://raw.githubusercontent.com/lennox0909/ML_and_DL_basic/master/slides/mini_batch_vs_stochastic_descent.JPG)
Slide from NTU李弘毅老師

## Recipe of Deep Learning
![](https://raw.githubusercontent.com/lennox0909/ML_and_DL_basic/master/slides/recipe_of_deep_learning_1.JPG)
![](https://raw.githubusercontent.com/lennox0909/ML_and_DL_basic/master/slides/recipe_of_deep_learning_2.JPG)
* Do not always blame Overfitting!
  * Could be not well-trained
* Dropout is a kind of Ensemble

## More notes
* Deep Learning: each neuron serves as a module to provide specific function (Modulization)
* End-to-end Learning
  * A very complex model, consists of many simple function, as a product line
* Emsemble Boosting: Improving weak classifiers
  * AdaBoost
  * Gradient Boosting
  * etc.






