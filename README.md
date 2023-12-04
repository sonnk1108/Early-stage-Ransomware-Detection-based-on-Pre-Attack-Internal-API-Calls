# Early-stage-Ransomware-Detection-based-on-Pre-Attack-Internal-API-Calls
In this project, I implemented some engineering techniques and improved the accuracy from 80 to 100%
Here are the details of the dataset : 
https://www.researchgate.net/publication/369242528_Early-Stage_Ransomware_Detection_Based_on_Pre-attack_Internal_API_Calls

In a preprocessing step, we create more features. We will divide APIs into 12 categories and calculate how many APIs are in each category. follow the details below :  

![image](https://github.com/sonnk1108/Early-stage-Ransomware-Detection-based-on-Pre-Attack-Internal-API-Calls/assets/64638305/1d915d16-26e9-40e7-a3f3-d45ac748a1ac)
![image](https://github.com/sonnk1108/Early-stage-Ransomware-Detection-based-on-Pre-Attack-Internal-API-Calls/assets/64638305/d83e2500-4848-425e-b777-8a9d4e950def)


Besides, we also calculate the total APIs in each application and the percentage of each category in total.  

We will run all datasets with 5203 examples and use cross-validation (CV=5) to evaluate the models, and use GridSearch to optimize hyperparameters for each model.  
![image](https://github.com/sonnk1108/Early-stage-Ransomware-Detection-based-on-Pre-Attack-Internal-API-Calls/assets/64638305/38b8505b-f52d-4980-a86c-ee9a251100a5)


 


 
