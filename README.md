# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2024

+ Team 1
+ Projec title: Algorithm Implementation and Evaluation
+ Team members
	+ Wang, Jingqi
	+ Yang, Wenjun
	+ Jiang, Tianyi
	+ Xu, Yonghao

+ Project summary: The theme of this project is about algorithm practice and analysis to help solve fairness perception in the machine learning process.

Algorithm 1: "Information Theoretic Measures for Fairness-aware Feature Selection" is a research field that aims to solve the problem of how to perform fairness-aware feature selection in machine learning tasks. In many practical applications, the data set may have features related to sensitive attributes, such as race, gender, etc., which may cause the model to learn bias or unfairness. Therefore, in order to ensure the fairness of the model, features need to be selected or transformed to eliminate potential bias. This research area explores how to use information theory methods to quantify the correlation between features and sensitive attributes, and proposes some fairness criteria for feature selection to ensure that the features learned by the model do not introduce unfairness.

Algorithm 2: "Learning Fair Representations" refers to the task of learning fair representations in machine learning. In many cases, due to bias or unfairness in the data set, the model may learn biased representations, resulting in unfair treatment of sensitive attributes. Therefore, the goal of learning fair representation is to adjust the representation of the data in such a way that the model does not rely too heavily on sensitive attributes during the learning process, thereby reducing or eliminating unfair treatment of these attributes. Research in this area aims to explore how to design algorithms and models to learn fair representations to ensure that the model's prediction results are not affected by sensitive attributes, thereby achieving fairer decision-making.

In this project, we used "compas-scores-two-years.csv", which contains a large amount of criminal information, including age, gender, jail time, race, and parameters of second arrest and imprisonment. By fitting various models, we initially confirmed some discrimination features. After adjusting the two algorithms, it is not difficult to find that the model trained by the algorithm has a more accurate accuracy. Both algorithms help us reduce the impact of discrimination factors on model accuracy.

**Contribution statement**: 
Algorithm 1: Yang Wenjun, Xu Yonghao 
Algorithm 2: Wang Jingqi, Jiang Tianyi
Presentation: Jiang Tianyi

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
