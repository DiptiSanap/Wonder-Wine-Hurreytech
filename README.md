# Wonder Wine - Predictive Model for Wine Variety

## Overview
This repository contains the code and files related to an NLP classification on Wine variety review dataset. The task involved building and training NLP classification models using two different techniques: CountVectorizer and BERT. The dataset exhibited a data imbalance challenge, which was addressed using two balancing techniques: undersampling and ensemble method (Random Forest). Additionally, a separate Jupyter Notebook was created for each model, along with another Jupyter Notebook that contains data visualizations and insights.

## Data Description
The dataset contains the following features:

* user_name: The user_name of the reviewer.
* country: The country from which the wine originates.
* review_title: The title of the wine review, often including the vintage.
* review_description: A detailed review of the wine provided by the customer.
* designation: The vineyard within the winery where the grapes for the wine are sourced.
* points: Ratings given by the user, ranging from 0 to 100.
* price: The cost of a bottle of the wine.
* province: The province or state from which the wine originates.
* region_1: The wine-growing area in a province or state, such as Napa.
* region_2: Sometimes, there are more specific regions specified within a wine-growing area (e.g., Rutherford inside the Napa Valley), but this value can sometimes be blank.
* winery: The winery that produced the wine.
* variety: The type of grapes used to make the wine.


## Repository Structure
The repository is organized as follows:

1. **Wonder_Wine_using_CountVectorizer.ipynb**: This Jupyter Notebook contains the code and steps for building and training the NLP classification model using the CountVectorizer technique. It includes data preprocessing, feature extraction, model training, evaluation, and testing.
Notebook link: 

2. **Wonder_Wine_using_BERT.ipynb**: This Jupyter Notebook contains the code and steps for building and training the NLP classification model using BERT. BERT is a powerful pre-trained transformer-based language model that excels in NLP tasks. The notebook covers data preprocessing, fine-tuning BERT, model evaluation, and testing.
Notebook link:

3. **Wonder_Wine_Visualisation_Insight.ipynb**: This Jupyter Notebook contains various data visualizations and insights related to the dataset. It helps in understanding the distribution of data, the class imbalance, and other important patterns in the data.
Notebook link:
   
4. **predictions.csv**: Predictions given by model on test.csv data
File link: 

5. **README.md**: The file you are currently reading, providing an overview of the repository and the assignment.
   
6. **License**: This project is open-source and distributed under the MIT License. Feel free to use, modify, and distribute the source code as per the terms and conditions of the MIT License. See the LICENSE file for more details.

## Results:
![image](https://github.com/DiptiSanap/Wonder-Wine-Hurreytech/assets/107847530/08a6e746-1bb0-41d6-a229-40b545eb0805)




## Conclusion
This repository houses all the necessary code files and data for the NLP classification task. It demonstrates the implementation of two different NLP classification techniques (CountVectorizer and BERT) and addresses the data imbalance challenge using undersampling and an ensemble method (Random Forest). The data visualization and insights notebook provide a deeper understanding of the dataset, which could be valuable for making informed decisions during the model training and evaluation process.
