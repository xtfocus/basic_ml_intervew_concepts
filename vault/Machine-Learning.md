# Machine-Learning questions

Regression:

1. What are the assumptions for LR to work?
2. How do you diagnose LR errors
3. L1 and L2 regularization: what's the difference. What's other regularization techniques?
4. Difference between Linear regression and Logistic regression
5. MLE vs OLS

I encountered 3 and 4, but I think it's helpful to know 1 and 2 so you can extend your answer (If you think 4 sounds silly, I came across sillier questions. Be prepared)

5 never appeared in my interviews, but it feels too important to miss: interviewers like asking about very basic stuff.

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

Got this question all the time. You should at least know PCA and t-SNE, and that PCA maximize difference between data points while tSNE do the opposite.

Optimization:

12. How to avoid overfitting? List some regularization techniques (just name them or go deep if it's your strength)
13. What does high-bias mean?
14. Why initialize a Neural Network with random weights? What if I use SGD with initial weights all set to 1?
15. How many optimization algorithms do you know? Explain each one in detail
16. Difference between SGD vs Gradient descent vs Minibatch Gradient descent
17. How cross-validation works
18. What techniques for ML on imbalanced datasets (sampling, weighting, and which metrics to optimize)

I faced some of these optimization question for an AI Engineer position and others for a Data Scientist position. These are the bread and butter if you have been sitting around playing with deep learning models.

NLP & Transformers:
19. Explain tf-idf formula
20. How many attentions are there in BERT?
21. In high-level, the difference between bag of words models, RNN, and BERT
22. Architecture of GRU and LSTM

I hate equation questions, but I faced 19 in an AI Engineer interview. 

For 20, 21, and other Transformers-related concepts, I already dedicated a [repo](https://github.com/xtfocus/aimesoft_interview), which also cover optimization concepts like gradient accumulation, so take a look.

For 21 and 22, my initial reaction was: aghh, the less cool models, why people still talk about them?! They want to challenge you, so be prepared.

LLMs:

23. Do you use them and how
24. Have you created a chat bot?
25. Describe the Mixture of Expert architecture

23 and 24: Everyone asked these in 2024. 25 is an advanced topic for a project using mostly basic ML models, but they asked anyway because I name-dropped it on my resume. The world is changing fast: LLM architectures may become a common interview topic in the near future. 

Now I have to go fix my resume.
