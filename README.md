# FTR_Project

# Image Analysis Using Azure Computer Vision And Azure Machine Learning

## Project Statement
Image analysis is the extraction of meaningfull information from the image. Analysis of images can give meaningful information including face detection, object detection, color scheme, gender detection, detect brand and various category. Using cognitive services provided by Azure Image Analysing web services will be made. This image analysis service will help us knowing the face, object and various elements in image. It can give us answers for who, when and where was the image taken.

## Azure Technology Used
1. Azure Computer Vision
2. Azure Machine Learning

## Prerequisites 
1. Azure Portal Subcription
2. Python

## Project Description 
The goal of this project is to develop an image analysis system using Azure's Cognitive Services and machine learning capabilities. The system will utilize various Azure services to process and analyze images, extract meaningful information from them, and provide valuable insights. The project will involve gathering a diverse dataset of images relevant to the target domain. Azure Machine Learning will be used to build and deploy advanced machine learning models for image analysis. This includes developing deep learning models. By leveraging Azure's Cognitive Services and machine learning capabilities, this project aims to create a robust and scalable image analysis system that can be utilized in various domains, such as healthcare, retail, security, and more. It can be used in daily life to identify objects like in cctv camera can detect and harmful object and using the enormous data set in computer vision. We can easy detect and object in the image. It can be used to train an AI robot to recognise things around itself. 

## Step-By-Step Implementation

### Creating Computer Vision Services

Firstly, login to Azure portal and search for cognitive services. In cognitive services, go for Computer Vision and click on create and fill details. After filling details the computer vision service will be created.

![image](https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/ec30bac5-4cc9-4a1e-9ac1-0625b4095fa6)

After filling all the details we will get our computer vision resource and we will have our subscription key and endpoint key.

<img width="1254" alt="Screenshot 2023-07-06 at 15 04 30" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/41302dd6-b8a1-416d-aa7c-1f485758450a">

Below image shows the subscription keys and Endpoint which will be required when we have to access to this service.

<img width="1209" alt="Screenshot 2023-07-06 at 15 06 29" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/4b49e9a4-f7fe-46d3-bc7e-b138a8143f82">

#### Create the Azure Machine Learing Resource

<img width="1792" alt="Screenshot 2023-07-06 at 15 25 38" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/54cf9cfb-8d88-4e48-8528-1a4ee4e056f0">

After creating the azure machine learing resource wait for deployment and start the machine

<img width="1214" alt="Screenshot 2023-07-06 at 15 27 42" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/f9746cc1-d3aa-4ab5-a0ee-9dd8ac917852">

We will code on jupyterlab application and we will use the notebook of python 3.8 - AzureML

<img width="1214" alt="Screenshot 2023-07-06 at 15 29 56" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/f1eeb6fe-aa9a-49f4-a0ea-3f198ded9cd1">

### Coding
Now, here is the snippet of code where we will authenticate the user access to the service, all the python libraries we are going to use and the input image we are going to take from the user.
We concantinate to the endpoint url what version of computer vision we want to use and for what purpose.
Here we use vision v3.1 for analysis

<img width="899" alt="Screenshot 2023-07-06 at 15 36 14" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/1a598e5a-7a04-4994-8e80-93e0bac31512">

We put one try and except block if anything is incorrect or the input image is invalid.

<img width="663" alt="Screenshot 2023-07-06 at 15 45 05" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/215c2396-3fec-4dde-9294-802a2890beb6">

We import json so that when all the analysis is done the result is shown to us in json format.
Matplotlib will be used for operations on the image.
The following snippet is where we display the input image and its corresponding analysis which will we shown in json.

<img width="663" alt="Screenshot 2023-07-06 at 15 46 15" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/b77cbb0d-39e3-4c92-9e3c-e021f5185700">

We can do futher analysis by calling the functions to analyse specific element of the image.
For example we want to highlight the faces in the given image so the following image is the snippent for that code.

<img width="788" alt="image" src="https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/04bbe8dd-8b91-40f2-90e7-9a082ecece58">

## Working/ Live Demo

https://github.com/Proyobro-lennox/FTR_Project/assets/85806856/1a7da472-f1cd-40f0-aeca-1060da22fd9b

## Project Link

[image_analysis_using_CV_ML.ipynb](url)








