# Machine Learning Specialization 
_provided by Coursera & University of Washington_
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
4. mmm
