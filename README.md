# Coursera-MachineLearning-notes
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
    - true positive: spam, be filtered
    - false negative: spam, not be filtered
    - false positive: not spam, be filtered
    - true negative: not spam, not be filtered
  - example: medical diagnosis
    - true positive: ill, be treated
    - false negative: ill, not be treated
    - false positive: not ill, be treated
    - true negative: not ill, not be treated
    
  |         | healthy         | cold             | flu         |
  |---------|-----------------|------------------|-------------|
  | healthy | healthy healthy | healthy negative | healthy flu |
  | cold    | cold healthy    | cold cold        | cold flu    | 
  | flu     | flu healthy     | flu cold         | flu flu     |
4. mmm
