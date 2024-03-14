# Machine-Learning.md

Regression:

1. What are the assumptions for LR to work?
2. How do you diagnose LR errors
3. L1 and L2 regularization: what's the difference. What's other regularization techniques?
4. Difference between Linear regression and Logistic regression
5. MLE vs OLS

I encountered 3 and 4, but I think it's helpful to know 1 and 2 so you can extend your answer (If you think 4 sounds silly, I came across sillier questions. Be prepared)

Tree models:
6. What's bagging vs boosting?
7. What's the difference between Random Forest, Gradient Boosting and XGBoost? (how each works, tendency to overfit, how fast they train, name some hyper-parameters)
8. How decision tree works? What's the optimization objective for decision tree

In real life I got the question "what are ensemble learning methods you know", to which the answer is bagging and boosting. But it's more helpful that you actually describe what something is, rather than just name it. *If there are too many methods, you should at least talk about the most basic ones in reasonable depth.*

I also got question 8. For this question, it helps to know both Entropy and Gini, for rambling sake.

Other classic models:
9. Summarize how SVM works? Explain in high-level what each SVM kernel do?

SVM is usually least expected in interviews, but I faced it. You probably would do OK if you forget the maths, but they expect you to understand it on high-level. This also tell you the interviewer takes textbook ML very seriously. Usually a good sign.

10. Steps in k-means algorithm

One of the easiest question you can ever get. A more advanced question would be about parallelized k-means, which luckily never showed up in my interviews, but in exams.

11. Dimension reduction methods you know

Got this question all the time. You should at least know PCA and tSNE, and that PCA maximize difference between data points while tSNE do the opposite.

Optimization:

6. How to avoid overfitting? List some regularization techniques (just name them or go deep if it's your strength)
7. What does high-bias mean?
8. Why initialize a Neural Network with random weights? What if I use SGD with initial weights all set to 1?
9. How many optimization algorithms do you know? Explain each one in detail
10. Difference between SGD vs Gradient descent vs Minibatch Gradient descent
11. How cross-validation works

I got 6, 8, and 10 for an AI Engineer position.

* Describe MoE architecture
