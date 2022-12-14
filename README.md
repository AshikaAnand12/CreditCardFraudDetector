# Credit Card Fraud Detection using Autoencoders

## Team Name: Dementors

## Team Members:

1. Ashika Anand Babu
2. Anusha Gangasani
3. Ramya Mahesh

## Contributions:
### Ashika Anand Babu
1. Implementation of Visualizations on Colab
2. Choosing the Model
3. Hyperparameter tuning
4. MLOps Visualization
5. Documentation

### Anusha Gangasani
1. Data Cleaning and Processing
2. Choosing the model
3. Hyperparamter tuning
4. Documentation
5. Model Deployment

### Ramya Mahesh
1. Choosing the Model
2. Hyperparameter tuning
3. Streamlit App Creation
4. Streamlit App Deployment
5. Documentation

## **Steps to run the project**:
1. Download creditcard.csv file from [Here]( https://drive.google.com/file/d/1KDJcnin4p1SeZGOsN-9y114isAkwTcu3/view?usp=sharing)
2. Upload .csv file to your drive
3. Run the colab
4. Provide permission to access the file in the colab

Or

1. Download creditcard.csv file from [Here]( https://drive.google.com/file/d/1KDJcnin4p1SeZGOsN-9y114isAkwTcu3/view?usp=sharing)
2. Upload the creditcard.csv file to sample_data in google cola
3. Run the colab

**Note:** Ppt, Video and report are included in the github repo

Colab link: https://colab.research.google.com/drive/1v1IVxKmASxota9691xDGLQ0itPdg2yLZ 

Video Link : https://drive.google.com/file/d/19u1na-wG3NxT9wiSRjudXd_JTs7KnXma/view?usp=share_link

## CI Pipeline
1. Upload data after downloading from above links - Data Injection
2. Data obtained has undergone PCA since it is confidential and we have performed cleaning and classification for fraud and normal records - Data preparation
3. Used autoencoder with 50 epochs for Model training
4. Model has been stored as ".h5" file

## CD Pipeline
1. Deployed model on. [[NEED TO DEPLOY]]
2. App UI can be accessed using [Streamlit](https://ramyamahesh1126-specialtopicsproject-app-cngff6.streamlit.app/))


## Steps for Streamlit App Creation
1. Create a Streamlit account
2. Create an app.py file to run the UI
3. Create a requirement file for all the dependencies
4. In the app.py file allow the user to upload data
5. Once the data is uploaded, prepare and process the data
6. Deploy the app on Streamlit using Github's app.py file

## Steps to use Streamlit
1. Access the [URL](https://ramyamahesh1126-specialtopicsproject-app-cngff6.streamlit.app/))
2. Upload the [data]( https://drive.google.com/file/d/1KDJcnin4p1SeZGOsN-9y114isAkwTcu3/view?usp=sharing)
3. Once the data is uploaded, view the visualizations 

