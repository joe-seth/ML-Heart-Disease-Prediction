# Heart Disease Prediction
![heart](https://media.istockphoto.com/id/1156928011/photo/heart-attack-heart-attack-conceptual-artwork-3d-illustration.jpg?s=612x612&w=0&k=20&c=A2kWPu_dG5vmcaKcfCGA6FVRRIHRJ83R0HhlAys5fK4=)

This notebook explores the prediction of heart disease using machine learning. We'll work with a heart disease dataset, aiming to detect the probability of a person being affected by a severe heart problem.
Key Takeaways

    Data Insight: We'll analyze the heart disease dataset to derive meaningful insights from the data.

    EDA (Exploratory Data Analysis): Exploring the data is a crucial step for obtaining valuable results.

    **Feature Engineering:** After understanding the data, we'll prepare the features for the model building phase.

    **Model Building:** We will develop machine learning models for heart disease detection.

## Libraries Used

    Pandas and Numpy for data analysis and manipulation.
    Matplotlib and Seaborn for data visualization.
    Scikit-Learn for model building and evaluation.

## Data Loading

The dataset is loaded using Pandas' read_csv function.
EDA and Data Analysis

    The dataset contains 303 rows, indicating a relatively small dataset.
    Most features are of integer type, with only one feature in float type.
    Fortunately, the dataset has no missing values.

## Correlation Analysis

We analyze the correlation between different features, which helps in understanding feature relationships.
Model Building

We split the dataset into training and testing sets and explore various machine learning algorithms, including K-Nearest Neighbors (KNN), to build the predictive model.
Feature Engineering

We prepare the dataset by categorizing features and scaling continuous variables to a common unit.
Modeling

    We split the dataset into training and testing sets.
    The K-Nearest Neighbors (KNN) algorithm is applied.
    The model achieves an accuracy of approximately 85.7%.
