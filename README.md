# Car Accident Analysis and Repair Cost Estimation

## Overview

This project focuses on utilizing deep computer vision techniques to analyze car accidents and estimate repair costs. The pipeline is designed to process images  of car accidents, identify key elements, and provide an estimation of the repair cost based on the severity of the damage.

## Project Pipeline

![Flowchart (1)](https://github.com/Hassen-Elmahrouk/Car-accident-analysis-and-repair-cost-estimation/assets/94080018/b0c91da2-1d22-41c4-9916-1579b6aaca66)



## Features
* AI Realness Check
Ensures the authenticity of car accident images using classification AI models , i tested  a simple CNN , efficientnet and transformers .

* Damage Severity Assessment
Used to categorize car damage into different severity levels ( moderate, severe and minor) , i tested  a simple CNN , efficientnet and transformers .

* Car parts segmentation 
Utilizes advanced algorithms, including YOLO, Mask R-CNN.

* Damage segmentation
Utilizes advanced algorithms, including YOLO, Mask R-CNN .

* Cost Prediction
I used llama2 7b to estimate the reparations cost range , the propmt used contains information about the accident extracted from previous steps.


## Getting Started


1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/Car-Accident-Analysis.git
2. Download pre-trained  Models  and Datasets : https://drive.google.com/drive/folders/1YLuYwf5tyKlYdcN_D41ZyfSAZ233Urqh?usp=sharing

## Demo

![img0](https://github.com/Hassen-Elmahrouk/Car-accident-analysis-and-repair-cost-estimation/assets/94080018/c5627d5d-d20e-4530-9737-13f72302f592)

* **LLama2 response :

![Screenshot 2024-01-14 013211](https://github.com/Hassen-Elmahrouk/Car-accident-analysis-and-repair-cost-estimation/assets/94080018/7954287a-cbc8-4349-8198-b07a7918755c)


