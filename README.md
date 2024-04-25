# Online Food Order Prediction

## What is it all about?
 - Food delivery companies use your buying habits to make the delivery process faster. The food order prediction system is one of the useful techniques these companies can use to make the entire delivery process fast.
 - These companies have so much data about their customers that they now know the food ordering habits of all customers. With this data, they can also predict whether or not a customer will order again from their app. It is a good technique for identifying areas, families and customer types with more business opportunities.
 - So in this project we will see how you can train a Machine Learning model to predict online food orders from a particular customer

## Data Description
- I have used the onlinefoods.csv file for the project
- The dataset contains information like:
1. the age of the customer
2. marital status of the customer
3. occupation of the customer
4. monthly income of the customer
5. educational qualification of the customer
6. family size of the customer
7. latitude and longitude of the location of the customer
8. pin code of the residence of the customer
9. did the customer order again (Output)
10. Feedback of the last order (Positive or Negative)

## Model Description
 - The model I have used is RandomForest, you can check the model's training process in the `food-prediction.ipynb` notebook

## Libraries Used
 - Numpy
 - Pandas
 - Matplotlib
 - Seaborn
 - Scikit-learn

## Evaluation Metrics
 - Accuracy: 0.8846153846153846 (88%)
 - Precision: 0.8809101346414778 (88%)
 - Recall: 0.8846153846153846 (88%)

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: `git clone https://github.com/NebeyouMusie/Online-Food-Order-Prediction.git`
 3. Create and Activate Virtual Environment (Recommended)
    - `python -m venv venv`
    - `source venv/bin/activate`
 4. Install Libraries: `pip install numpy pandas matplotlib seaborn scikit-learn`
 5. Open `food-prediction.ipynb` and run all cells
 6. Or you can download the `onlinefoods.csv` and `food-prediction.ipynb` file from the repository, upload those files to [Google Colab](https://colab.research.google.com/) then run all the cells in the `food-prediction.ipynb` Notebook

## Acknowledgments
 - I would like to thank [Aman Kharwal](https://www.linkedin.com/in/aman-kharwal)
    
