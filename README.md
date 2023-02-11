# South African SONA Speech President Predictor

> Using text from the SONA speeches from 1994 to 2022 as input to a artificial neural network classifier to predict president. 

<img src="sa.webp" width="700" height="370">


## Introduction

This project aims to **predict the South African president based on their State of the Nation Address (SONA) speeches**. The text data used for this project is from SONA speeches from 1994 to 2022. This project makes use of Artificial Neural Network (ANN) classifier and other widely-used classifiers to compare and benchmark the accuracy and classifications.

## Data

The data used for this project is the text from the SONA speeches of the South African presidents from 1994 to 2022. The text data was pre-processed and cleaned for analysis. Pre-processing involved applications of NLP to clean the text and vectorize it - we applied a bag-of-words approach to use as input for Neural Network structures. 

## Classifiers/Methods

The following classifiers were used for this project:
<br>
- **Artificial Neural Network (ANN)**
    * a basic machine learning model that uses a series of interconnected nodes to process and classify data.

<br>

- **Multinomial Logistic Regression**
    * type of regression analysis used for multi-class classification problems. It uses a linear combination of the input features to make predictions and assigns a probability to each class.

<br>

- **Decision Trees**
    * type of machine learning algorithm that makes predictions by recursively dividing the data into subsets based on certain rules. It is a simple and interpretable model.

<br>

- **Random Forests**
    *  an ensemble learning algorithm that combines multiple decision trees to make predictions. It uses random sampling of the data and features to construct multiple trees and aggregates the predictions of each tree to make a final prediction

<br>

- **Gradient Boosted Machines**
    * type of machine learning algorithm that uses an ensemble of decision trees to make predictions. It uses gradient descent to iteratively improve the predictions of each tree in the ensemble. 

The results of the ANN classifier were compared and benchmarked with the results of the other classifiers.

## Results

The Multinomial Logistic Regression classifier had the best accuracy at almost $60\%$. The results of the ANN classifier were also compared and benchmarked with the results of the other classifiers.

## Conclusion

This project shows that text data from the SONA speeches can be used to predict the South African president. The Multinomial Logistic Regression classifier had the best accuracy among the classifiers used in this project. This project can be used as a basis for further research in the field of text analysis and prediction.

## Getting Started

This project is implemented in R programming language. To run this project, the following software and packages are required:

- R
- R Studio
- Caret Package
- keras
- tensorflow
- tidyverse
- tidytext

To run this project, clone or download the repository and open the R project file in R Studio. The code and data are included in the repository.

## Contributions

If you want to contribute to this project, feel free to submit a pull request or open an issue in the repository.

## Contact

For any questions or queries, please email: sngpav003@myuct.ac.za



