# DSC180A Methodology Assignment 5, Task 2

Name: Emily Chen

UCSD Email: e6chen@ucsd.edu

**1. What is the most interesting topic covered in your domain this quarter?**
The most interesting topic covered in my domain this quarter is activity based travel models. The underlying priciple behind the model is that a demand for travel is built on people's daily activity. It's interesting to see how this model plays a role in forecasting travel within a region and how small parts of our lives and background can influence how we travel. The implications of these types of model can help cities and organizations, such as SANDAG, make policy decisions that will best suit the needs of their residents. 

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
In Quarter 1, we implemented a multinomial logistic regresssion to predict vehicle type, as a replication to the current ABM. A potential investigation I would like to pursue in the next Quarter would be investigating other vehicle data (age, fuel type, etc), understanding how these factors can impact someone's decision in choosing a vehicle, and how their vehicle choice impacts their travel decisions. 

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
A potential change I would like to make in the current approach would be to utilize different machine learning algorithms. This quarter, we faced an issue with class imbalance for the vehicle type data. To mitigate this issue, I've done random undersampling of the majority classes while using different metrics, such as AUC/ROC, F Score, and Precision-Recall to get a large picture of how the model is performing. The model's overall performance doesn't change much with these preprocessing methods, so I hope to implement a more advanced algorithm, such as decision trees or boosting algorithms. 

**4. What other techniques would you be interested in using in your project?**
Other techniques I've looked into regarding class imbalance is over-generating synthetic samples of minority class (SMOTE), cost-sensitive learning, and hybrid approaches to over and undersampling to achieve better results. These approaches can help mitigate the challenges of the model underperforming through balancing the class distribution or penalizing misclassification that will allow the model to focus on correctly identifying minority classes. Perhaps, even using different features of the model could be more indicative of the vehicle type. 
