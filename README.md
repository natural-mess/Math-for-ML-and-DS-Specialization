# [Mathematics for Machine Learning and Data Science Specialization](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science)
Fundamental mathematics toolkit of machine learning: calculus, linear algebra, statistics, and probability.

Mathematics for Machine Learning and Data Science is a foundational online program created by DeepLearning.AI and taught by Luis Serrano. In machine learning, you apply math concepts through programming. And so, in this specialization, you’ll apply the math concepts you learn using Python programming in hands-on lab exercises. As a learner in this program, you'll need basic to intermediate Python programming skills to be successful.

Many machine learning engineers and data scientists need help with mathematics, and even experienced practitioners can feel held back by a lack of math skills. This Specialization uses innovative pedagogy in mathematics to help you learn quickly and intuitively, with courses that use easy-to-follow visualizations to help you see how the math behind machine learning actually works. 

We recommend you have a high school level of mathematics (functions, basic algebra) and familiarity with programming (data structures, loops, functions, conditional statements, debugging). Assignments and labs are written in Python but the course introduces all the machine learning libraries you’ll use.

## [Course 1: Linear Algebra for Machine Learning and Data Science](https://www.coursera.org/learn/machine-learning-linear-algebra?specialization=mathematics-for-machine-learning-and-data-science)

- Represent data as vectors and matrices and identify their properties using concepts of singularity, rank, and linear independence
- Apply common vector and matrix algebra operations like dot product, inverse, and determinants
- Express certain types of matrix operations as linear transformation, and apply concepts of eigenvalues and eigenvectors to machine learning problems

### [Week 1: System of linear equations](Course1-Linear-Algebra/Week1/)
Matrices are commonly used in machine learning and data science to represent data and its transformations. In this week, you will learn how matrices naturally arise from systems of equations and how certain matrix properties can be thought in terms of operations on system of equations.

### [Week 2: Solving system of linear equations](Course1-Linear-Algebra/Week2/)
In this week, you will learn how to solve a system of linear equations using the elimination method and the row echelon form. You will also learn about an important property of a matrix: the rank. The concept of the rank of a matrix is useful in computer vision for compressing images.

### [Week 3: Vectors and Linear Transformations](Course1-Linear-Algebra/Week3/)
An individual instance (observation) of data is typically represented as a vector in machine learning. In this week, you will learn about properties and operations of vectors. You will also learn about linear transformations, matrix inverse, and one of the most important operations on matrices: the matrix multiplication. You will see how matrix multiplication naturally arises from composition of linear transformations. Finally, you will learn how to apply some of the properties of matrices and vectors that you have learned so far to neural networks.

### [Week 4: Determinants and Eigenvectors](Course1-Linear-Algebra/Week4/)
In this final week, you will take a deeper look at determinants. You will learn how determinants can be geometrically interpreted as an area and how to calculate determinant of product and inverse of matrices. We conclude this course with eigenvalues and eigenvectors. Eigenvectors are used in dimensionality reduction in machine learning. You will see how eigenvectors naturally follow from the concept of eigenbases.

## [Course 2: Calculus for Machine Learning and Data Science](https://www.coursera.org/learn/machine-learning-calculus?specialization=mathematics-for-machine-learning-and-data-science)

- Analytically optimize different types of functions commonly used in machine learning using properties of derivatives and gradients 
- Approximately optimize different types of functions commonly used in machine learning
- Visually interpret differentiation of different types of functions commonly used in machine learning
- Perform gradient descent in neural networks with different activation and cost functions

### [Week 1: Derivatives and Optimization](Course2-Calculus/Week1/)

### [Week 2: Gradients and Gradient Descent](Course2-Calculus/Week2/)

### [Week 3: Optimization in Neural Networks and Newton's Method](Course2-Calculus/Week3/)

## [Course 3: Probability & Statistics for Machine Learning & Data Science](https://www.coursera.org/learn/machine-learning-probability-and-statistics?specialization=mathematics-for-machine-learning-and-data-science)

- Describe and quantify the uncertainty inherent in predictions made by machine learning models
- Visually and intuitively understand the properties of commonly used probability distributions in machine learning and data science
- Apply common statistical methods like maximum likelihood estimation (MLE) and maximum a priori estimation (MAP) to machine learning problems
- Assess the performance of machine learning models using interval estimates and margin of errors 

### [Week 1: Introduction to Probability and Probability Distributions](Course3-Probability-Statistics/Week1/)
In this week, you will learn about probability of events and various rules of probability to correctly do arithmetic with probabilities. You will learn the concept of conditional probability and the key idea behind Bayes theorem. In lesson 2, we generalize the concept of probability of events to probability distribution over random variables. You will learn about some common probability distributions like the Binomial distribution and the Normal distribution.

### [Week 2: Describing probability distributions and probability distributions with multiple variables](Course3-Probability-Statistics/Week2/)
This week you will learn about different measures to describe probability distributions as well as any dataset. These include measures of central tendency (mean, median, and mode), variance, skewness, and kurtosis. The concept of the expected value of a random variable is introduced to help you understand each of these measures. You will also learn about some visual tools to describe data and distributions. In lesson 2, you will learn about the probability distribution of two or more random variables using concepts like joint distribution, marginal distribution, and conditional distribution. You will end the week by learning about covariance: a generalization of variance to two or more random variables.

### [Week 3: Sampling and Point estimation](Course3-Probability-Statistics/Week3/)
This week shifts its focus from probability to statistics. You will start by learning the concept of a sample and a population and two fundamental results from statistics that concern samples and population: the law of large numbers and the central limit theorem. In lesson 2, you will learn the first and the simplest method of estimation in statistics: point estimation. You will see how maximum likelihood estimation, the most common point estimation method, works and how regularization helps prevent overfitting. You'll then learn how Bayesian Statistics incorporates the concept of prior beliefs into the way data is evaluated and conclusions are reached.

### [Week 4: Confidence Intervals and Hypothesis testing](Course3-Probability-Statistics/Week4/)
This week you will learn another estimation method called interval estimation. The most common interval estimates are confidence intervals and you will see how they are calculated and how to correctly interpret them. In lesson 2, you will learn about hypothesis testing where estimates are formulated as a hypothesis and then tested in the presence of available evidence or a sample of data. You will learn the concept of p-value that helps in making a decision about a hypothesis test and also learn some common tests like the t-test, two-sample t-test, and the paired t-test. You will end the week with an interesting application of hypothesis testing in data science: A/B testing.