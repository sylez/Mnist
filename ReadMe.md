# Introduction
Patter recognition homework.  
Use various methods on mnist dataset.
# Method
## KNN
|method | accuracy|
|---- | ----|
|vector nomalized to norm 1 | 97.3 |
|use lenet5 extract features| 99.01 |
|image distortion model|  99.15 |
|output layer softmax as feature| 99.6 |

## SVM
|method | accuracy |
| --- | --- |
|output layer without softmax as feature| 99.68|

## CNN
|architecture | method | accuracy |
|----|----|----|
|conv-4,fc-1|batch norm, SGD with momentum, learning rate decay | 99.44|
|capsule net|  |99.7 |
