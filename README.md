# Plant Disease Prediction

This is a smart streamlit based app which can be used for the early detetction of the plant diseases just by uploading a picture of the plant. The prediction is based on the hundreds of photos used in the dataset. The application is easy to use and helpful for disease prediction.

## Screenshots
<img src= "![Screenshot 2024-08-15 024936](https://github.com/user-attachments/assets/9aa5b95b-0b65-4f93-b495-18bcc880158a)" width "200" />

<img src="https://[user-images.githubusercontent.com/link-to-your-image.png](https://github.com/user-attachments/assets/984541b0-1985-4a6d-bf63-e77d98dcbd90)" width="200" />

## Tech Stack


**TensorFlow** : Machine learning
**NumPy** : Numerical operations
**Streamlit** : Web app interface
**Docker** : Containerization
**Python** : Programming language



## Kaggle Dataset
Kaggle Dataset Link: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

## Download and Copy below training model in the trained_model folder present in app
Trained Model Link: [[https://drive.google.com/file/d/1i466c4XOs048Q54EPCqgzoG8zWcARnrj/view?usp=sharing](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=sharing)](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link)https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link

## Install libraries
npm install numpy tensorflow streamlit

## Steps to run on using streamlit
1) Go to the project file and open with a code editor
2) Change directory to app
3) Run this command: streamlit run main.py

## Steps to run using Docker container
1) Go to Command prompt
2) Run command: docker run -p 80:80 plant-disease-prediction-image:v1.0
3) To see all the images, run command: docker images
