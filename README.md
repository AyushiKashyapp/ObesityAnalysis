# ObesityAnalysis

This study explores the social-structural foundations of obesity by investigating how individuals’ positions within their egocentric social networks influence body mass index (BMI). Previous findings suggest that individuals occupying a bridge position within their network get access to a variety of non-repetitive information which impacts their BMI.

The study is done using a multivariate analysis of nationally representative data on older Americans. It was found that occupying a bridging position within a network allows better access to health-related knowledge and impacts the likelihood of being obese. These findings highlight the significance of considering social network position and the role of individual connection in understanding the structural bases of health issues like obesity.

This study extends on a previous study by including more impactful features related to an individual’s critical health status and modelling them using logistic regression and decision tree, dimensionality reduction using t-SNE, and clustering using K-Means, providing a comprehensive understanding of the dataset and significant predictors of obesity. The interaction of personal demographic, social network, and critical health features offer valuable insights into health disparities and development of potential strategies for addressing obesity.

## Model 1
[Model1]([url](https://github.com/AyushiKashyapp/ObesityAnalysis/blob/main/Model%201/Model-1.pdf)) examines the bi-variate relationship between Obesity and Bridge with a Logistic Regression model. The variable Bridge is the independent variable and obesity is the dependent variable. 

## Model 2
[Model2]([url](https://github.com/AyushiKashyapp/ObesityAnalysis/blob/main/Model%202/Model-2.pdf)) examines a multivariate relationship between Obesity and Bridge alongside other social network measures using the Logistic Regression and Decision Tree models. Obesity remains the dependent variable and Bridge along side other social network features are the independent variables.

## Model 3
[Model3]([url](https://github.com/AyushiKashyapp/ObesityAnalysis/blob/main/Model%203/Model-03.pdf)) builds on Model 2 and includes more variables describing the personal demographics and the social network structure of the respondent. The structure of data used is examined using [t-SNE and k-Means]([url](https://github.com/AyushiKashyapp/ObesityAnalysis/blob/main/Model%203/kmeans_tsne.pdf)). The dependent variable remains Obesity and its association with other features is computed using Logistic Regression and Decision Tree.

## Model 4
[Model4]([url](https://github.com/AyushiKashyapp/ObesityAnalysis/blob/main/Model%204/Model-4.pdf)) extends Model 3 and includes Critical Health Conditions into the analysis using Logistic Regression and Decision Trees. The structure of data used is examined using [t-SNE_k-Means]([url](https://github.com/AyushiKashyapp/ObesityAnalysis/blob/main/Model%204/kmeans_tsne.pdf)). These factors are included to study the impact of an individual’s bridging potential in the presence of features which are shown to have a strong association with obesity [6]. This model intends to test the significance of bridging potential for predicting obesity while considering the very directly related critical health conditions.
