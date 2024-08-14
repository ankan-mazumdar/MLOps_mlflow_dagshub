# MLOps Prototype mlflow UI and dagshub.com
This summary encapsulates the key steps you took in your ML Ops prototype, highlighting the use of MLflow for tracking, comparing, and deploying models, and the public production deployment using DagsHub.

### **Step 1: Experiment Setup**
- **Environment**: MLflow was used as the primary tool for tracking experiments and managing models.
- **Synthetic Dataset**: A synthetic dataset was created and utilized to train four different machine learning models.
- **Experiment Tracking**: Each model's performance was tracked within the MLflow UI, under the "Experiments" tab.

### **Step 2: Model Training**
- **Models Trained**:
  - XGBoost Classifier with SMOTE
  - XGBoost Classifier (without SMOTE)
  - Random Forest
  - Logistic Regression
- **Metrics Evaluation**: Each model was evaluated based on key metrics such as accuracy, F1 score, recall, etc., as displayed in the MLflow UI.

### **Step 3: Model Comparison**
- **Comparison of Models**: Using the MLflow UI, a parallel coordinates plot was generated to visually compare the performance of the four models based on various parameters (e.g., `eval_metric`, `max_depth`).
- **Selection**: Based on the comparison, the XGBoost Classifier with SMOTE was identified as the best-performing model.

### **Step 4: Deployment Strategy**
- **Challenger and Champion Concept**:
  - The selected XGBoost Classifier with SMOTE was designated as the "Champion" model and deployed.
  - A second model was chosen as a "Challenger" to be used for comparison against the Champion model in production.
- **Model Registration**: The models were registered in the MLflow Model Registry, and an alias was added for the model version (e.g., "challenger").

### **Step 5: Productionization**
- **DagsHub Integration**: The final step was to integrate the MLflow tracking server with DagsHub, enabling the production deployment of the chosen model to a public URL.
- **Public Access**: The deployed model and its experiments are accessible via a public URL on DagsHub, allowing for ongoing monitoring and evaluation.

### **Outcome**
- **ML Ops Pipeline**: The entire ML Ops pipeline, from experiment tracking to model deployment, was successfully implemented using MLflow and DagsHub, ensuring a reproducible and scalable machine learning workflow.

 
 ![image](https://github.com/user-attachments/assets/41ae2113-5eb5-48fe-a2fe-df0d9e2b7ae4)

 
 
 ![image](https://github.com/user-attachments/assets/ae3d504a-ed6e-4ed5-bc0b-ae2e7d6db761)


![image](https://github.com/user-attachments/assets/19d1fd7e-6d38-4bc6-800d-720ff35bbb35)


![image](https://github.com/user-attachments/assets/cb1ee241-969f-4180-9ecb-e07536e015dd)


![image](https://github.com/user-attachments/assets/555d6673-0279-42aa-9990-60f292310405)

![image](https://github.com/user-attachments/assets/41fca87d-beba-47d0-8157-fef9555de50a)

![image](https://github.com/user-attachments/assets/aab26320-0c38-4e0f-95e5-ec77199fea50)

![image](https://github.com/user-attachments/assets/bb9d77a8-d349-486c-b3b8-2ebc0d0e68f0)

![image](https://github.com/user-attachments/assets/6f87f0a0-d137-4809-a56e-4bdc908a7bce)

![image](https://github.com/user-attachments/assets/49bc5c87-b56d-49b4-9294-6d4ab4d7bae5)


![image](https://github.com/user-attachments/assets/898d34c4-47b9-4c68-813f-dca141b7c93c)



![image](https://github.com/user-attachments/assets/570be1fe-5eee-4066-85e4-0d29e2ba4526)


![image](https://github.com/user-attachments/assets/3e259731-4304-47f7-b555-a38ffec8c470)


![image](https://github.com/user-attachments/assets/732d8777-ccb4-4051-987d-9126a939e5e8)


![image](https://github.com/user-attachments/assets/9eb521a5-3508-4245-bca6-ba4f0d26e149)


![image](https://github.com/user-attachments/assets/e160fd7a-9b47-418e-a3b6-111fee5032dc)

![image](https://github.com/user-attachments/assets/491a39ec-a48d-4eca-8908-c585f52f2ee7)

![image](https://github.com/user-attachments/assets/37bb65d5-7738-4fdf-ad82-0eae68f9e6e4)

![image](https://github.com/user-attachments/assets/d2202e3f-5932-4d2e-a4f2-01957581fd2f)



![image](https://github.com/user-attachments/assets/6d6b1d72-7849-4b56-a335-85256c16a0e9)



![image](https://github.com/user-attachments/assets/d628a8a0-2da6-44e5-aa9d-bd27b18e4696)

![image](https://github.com/user-attachments/assets/364c0a70-f66c-46ae-bfc7-9f1f642b8d2e)



