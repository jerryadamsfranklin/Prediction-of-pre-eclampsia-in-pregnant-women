#A case study on handling imbalanced datasets

Niyati Chopra, Jerry Adams Franklin, Manaswini Nagaraj

Most machine learning classification algorithms are designed under the assumption that each class has an equal number of examples to learn from in the dataset, but real-world data doesn't always reflect that assumption. A dataset is said to be imbalanced if the number of samples for one of the classes is higher than the other class. The class that has a higher number of samples is called the majority class and the class that has a lower number of examples is called the minority class. 
When a machine learning model is fed with an imbalanced dataset, it tends to be biased towards the majority class and thus performs poorly on the minority class, thereby reducing the overall performance of the model. The effect of modeling or predicting using imbalanced data can cause greater damage than good. 
For example in fields like healthcare, where certain health conditions are rare and doctors cannot afford to incorrectly diagnose a patient, the effect of incorrect diagnosis due to imbalanced data could be extremely dangerous to the patient. Most real-world data has some imbalance naturally, a slight imbalance is often not a concern but a severe class imbalance can pose challenges to modeling and may require the use of special techniques to handle the imbalance. Techniques to handle imbalanced data include allocating different costs to training examples and re-sampling the available data, by either over-sampling the minority class or undersampling the majority class. 
In this case study, we will explore different techniques to over-sample the minority class applied on a pre-eclampsia dataset



