<h1 align="center">
             MedHelp HackHealth 🩺 💊 💉
</h1>
  
  ![image](https://user-images.githubusercontent.com/78029145/153434524-ca6c416b-3f8e-43ca-8174-6f68789209a5.png)

## Overview of the App

This app is used to predict the current medical state of an individual regarding 3 most common diseases and also includes a section which will provide some medical guidelines to anyone who is affected by any common disease from the disease prediction section.

The disease sections include ->

**1. Covid-19 Prediction Section**

**2. Diabetes Prediction Section**

**3. Heart Disease Prediction Section**

## Tech Stacks Used

<img src="https://img.shields.io/badge/html5%20-%2314354C.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%2314354C.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%2314354C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/> <img src="https://img.shields.io/badge/mysql%20-%2314354C.svg?&style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/php%20-%2314354C.svg?&style=for-the-badge&logo=php&logoColor=white"/>

## Libraries Used

<img src="https://img.shields.io/badge/numpy%20-%2314354C.svg?&style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/pandas%20-%2314354C.svg?&style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/pickle%20-%2314354C.svg?&style=for-the-badge&logo=pickle&logoColor=white"/>
<img src="https://img.shields.io/badge/flask%20-%2314354C.svg?&style=for-the-badge&logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/scikitlearn%20-%2314354C.svg?&style=for-the-badge&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/html5%20-%2314354C.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%2314354C.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%2314354C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/>

## Structure Of The Project

- The home page consists of cards which contains the links to 4 different web pages in which 3 are medical prediction section and 1 is medical guideline section.
- The prediction sections include - Diabetes Prediction, Covid-19 Prediction, Heart Disease Prediction.
- Each prediction page is conneceted with a Machine Learning Model which uses Random Forest Classifier to predict whether the user is affected by that disease or not.
- Also we have 3 different datasets used for training each of the machine learning model. The models are then stored in a pickle file and connected with the web pages using Flask.
- Each of the 3 web pages associated with prediction contains forms which take 4 different feature as input from the user in a given specified range in number format.
- The value entered in the forms are then fed into each of the individual models for getting the prediction. According to the predicted values the user is alerted whether they are a victim to that disease or not.
- The most relevant features are taken into consideration for prediction also these features can be found out with simple tests or analysis without visiting any doctor.
- So the victim can get a broad overview of their health condition specially regarding 3 most common diseases without any kind of doctor appointments.

## The features taken into consideration

| Disease | Features |
| - | - |
| Covid-19 | Dry Cough, Fever, Sore Throat, Breathing Problem |
| Diabetes | Glucose, Insulin, Body Mass Index, Age |
| Heart Disease | Chest Pain, Blood Pressure, Cholestrol, Max Heart Rate |

The feature selection is carefully done under the supervision of a medical science student.

## Model Deployment

- The app is deployed using python library -> Flask and finally deployed on Heroku.

## Future Prospects

- Addition of more disease prediction sections to cover more segments of medical domain
- Inclusion of a NLP chatbot for users to get advice regarding their diet and nutrition chart 
- Addition of a quiz section which will take inputs about the common diseases covered in the application and mark them as wrong and right to give users a detailed info regarding their disease

## UI Of The Web Application

### 1. Home Page
<pre>
<img src="https://user-images.githubusercontent.com/84087089/164988541-498cf845-3666-41fd-982c-abd43482e579.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988647-4af71edd-95b5-4b9f-b0d3-41e4ec289b28.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988705-176b454f-8fdb-4b11-988b-a9ee23047739.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988717-36094682-1b87-4165-a93c-a4a31fcd68eb.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988728-f215cb18-fd7c-41e3-901a-ac5e6a1e69b6.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988734-462aff9a-d872-4e64-837c-b225cb025346.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988742-9d77b7fc-dabe-4330-a2a0-64746d3db3c8.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988759-b89096a6-fea8-4f47-bb32-2e5ce2f03327.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988770-9f1f771a-f201-4c47-baef-7e8816ea40d0.PNG" width="1010"> <img src="https://user-images.githubusercontent.com/84087089/164988777-e19603e7-57fb-4532-a744-af1ae25aa7ff.PNG" width="1010"> 
</pre>

### 2. Diabetes Prediction Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/158956887-0b407b26-1971-4957-af43-a15bfc173f50.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/158956941-cac3a5c6-314d-46c0-87dc-96082dd328c0.png" width="1000">
</pre>

### 3. Covid-19 Prediction Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/158957322-5e76792c-201e-4743-8a74-2b2c736d3b40.png" width="1010"> <img src="https://user-images.githubusercontent.com/78029145/158957381-87c25f0b-3559-40d8-b911-b6f6b5fc4a50.png" width="1010">
</pre>

### 4. Heart Disease Prediction Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/158957765-d229878e-c2b7-45fb-9006-2bd05082b953.png" width="1010"> <img src="https://user-images.githubusercontent.com/78029145/158957853-bdc7aafd-3975-4825-bc31-f4c407e69542.png" width="1010">
</pre>

### 5. Medical Suggestions Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/159028682-8e8769d5-e588-4fce-96ea-05223d01f55f.png" width="1010"> <img src="https://user-images.githubusercontent.com/78029145/159028764-3ad5b97d-cb24-4766-a205-07aee4675c98.png" width="1010"> <img src="https://user-images.githubusercontent.com/78029145/159028835-b06ff20e-bc4e-4a05-9e28-219b94a46c64.png" width="1010">
</pre>

## Run Locally

Open Anaconda Prompt -

1.1 `git clone <repo link>`

1.2 `cd MedHelp-HackHealth`

1.3 `pip install -r requirements.txt `

1.4 `python run app.py`
