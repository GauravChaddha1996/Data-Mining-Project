# Data-Mining-Project
Project created for "Data mining concepts and techniques" course. 

### Project problem

Use the zoo dataset to design a neural network based classification system to predict the species of an animal. You should use a K-fold validation strategy to judge the overall accuracy of your system. Does the accuracy of the system change when you vary the number of folds to use. 

### Solution

I’ve been able to make a neural network based classification system to predict the species of an animal with an accuracy score of **97.14%** using a **K=5** fold validation strategy to judge the overall accuracy of my system. 


Yes, the accuracy of the system varies when we change the number of folds. It increases till K=5 and then decreases and stabilizes around 95.00-96.00% even if we increase the epochs parameter. The accuracy varies as such with K (No. of folds):

| No. of folds  | Accuracy      |
| ------------- |:-------------:| 
| 2             | 96.02         |
| 3             | 97.03         |
| 4             | 97.04         |
| 5             | 97.14         |
| 6             | 96.08         |
| 7             | 94.22         |
| 8             | 95.11         |
| 9             | 95.12         |
| 10            | 96.00         |
| 12            | 95.02         |
| 15            | 95.01         |
| 20            | 95.00         |

I’ve used ‘type’ attribute as label, Z-transformation method to normalize the data, a deep learning model with epochs = 1000. I’ve used accuracy and classification error as my performance metrics.

### Screenshots of solution and output

![Solution1](https://github.com/GauravChaddha1996/Data-Mining-Project/blob/master/solution1.png)
![Solution2](https://github.com/GauravChaddha1996/Data-Mining-Project/blob/master/solution2.png)
![Output](https://github.com/GauravChaddha1996/Data-Mining-Project/blob/master/output.png)
