# Machine Learning Specialization 
_provided by University of Washington & Coursera_
#### Table of Contents
1. [Machine Learning Foundations](#anchor_1)<br/>

## Machine Learning Foundations: A Case Study Approach<a name="anchor_1"></a>
1. regression
2. classification
3. confusion matrix
    |          | positive       | negative       |
    |----------|----------------|----------------|
    | positive | true positive  | false negative |
    | negative | false positive | true negative  |
  - example: spam email
    |          | filtered             | not filtered             | 
    |----------|----------------------|--------------------------|
    | spam     | spam filtered TP     | spam not filtered FN     |
    | not spam | not spam filtered FP | not spam not filtered TN |
  - example: medical diagnosis
    |         | treated            | not treated            | 
    |---------|--------------------|------------------------|
    | ill     | ill treated TP     | ill not treated FN     | 
    | not ill | not ill treated FP | not ill not treated TN |
  - multiclasses
    |         | healthy         | cold             | flu         |
    |---------|-----------------|------------------|-------------|
    | healthy | healthy healthy | healthy negative | healthy flu |
    | cold    | cold healthy    | cold cold        | cold flu    | 
    | flu     | flu healthy     | flu cold         | flu flu     |
4. classification flow
    <br><img src="https://github.com/Makiato1999/note-ML/blob/main/image/foundation/week3.png"  width="500" height="300">
5. week3 Assignment: 
    - classification, Logistic regression, supervised
    - [Analyzing product sentiment](https://github.com/Makiato1999/note-ML/tree/main/Foundations/Week3)
6. cluster flow
    <br><img src="https://github.com/Makiato1999/note-ML/blob/main/image/foundation/week4.png"  width="500" height="300">
7. week4 Assignment: 
    - classification, K-nearest neighbors(KNN), supervised
    - [Retrieving Wikipedia articles](https://github.com/Makiato1999/note-ML/tree/main/Foundations/Week4)
8. Collaborative filtering
    - SVD(Singular Value Decomposition), [details(简中)](https://www.cnblogs.com/pinard/p/6251584.html)
    - PCA(Principal component analysis), (I remember this is my COMP4360 last chapter, pretty interesting)
9. Recommender systems ML block diagram
    <br><img src="https://github.com/Makiato1999/note-ML/blob/main/image/foundation/week5.png"  width="500" height="300">
1. recall & precision
    - recall: (#liked & shown) / #liked
    - precision: (#liked & shown) / #shown
    - <br><img src="https://github.com/Makiato1999/note-ML/blob/main/image/foundation/week5r&p.png"  width="500" height="300">
2. no-linear features with neural network
    - <br><img src="https://github.com/Makiato1999/note-ML/blob/main/image/foundation/week6&||.png"  width="500" height="300">
    - <br><img src="https://github.com/Makiato1999/note-ML/blob/main/image/foundation/week6xor.png"  width="500" height="300">
        
