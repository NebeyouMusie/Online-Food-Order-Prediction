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

# Language Detection
 - A language detection model is a type of artificial intelligence (AI) that can identify the language a piece of text is written in.  These models are often used in machine translation applications, where they can automatically determine the source language of a text so that it can be translated into the correct target language.  Language detection models can also be used to categorize and sort information, or to filter content based on language.
   
## What's its usecase?
 - Language detection models have a wide range of applications, here are some of the most common:
    - **Machine translation**:  By identifying the source language of text, translation services can automatically choose the right translation model for the job,  leading to more 
      accurate and relevant translations.
    - **Content management**:  Large organizations that deal with information in multiple languages can use language detection to automatically sort and categorize documents according to 
      the language they're written in. This makes it much easier to find specific information.
    - **Customer service**: Companies with a global customer base can use language detection to route customer inquiries to agents who speak the appropriate language. This improves 
      customer satisfaction and ensures that customers get the help they need quickly.
    - **Web search**: Search engines use language detection to ensure users get the most relevant results for their queries. By identifying the language a search term is in, the search 
      engine can return results in that language.  
    - Google Translate is one of the most popular language translators in the world which is used by so many people around the world. It also includes a machine learning model to detect 
      languages that you can use if you don’t know which language you want to translate.
 - So in this project we will see how you can train a Machine Learning model to detect a language

## Data Description
- I have used the `language.csv` file for the project
- The dataset contains two columns namely:
1. Text - sentence for the respective language
2. language - name of the language

## Algorithm Description
 - The algorithm I have used is Multinomial Naïve Bayes algorithm to train the language detection model as this algorithm always performs very well on the problems based on multiclass classification, you can check the model's training process in the `language-detection.ipynb` notebook

## Libraries Used
 - Numpy
 - Pandas
 - Scikit-learn

## Score
 - Score: 0.9416909620991254 (94%)

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: git clone https://github.com/NebeyouMusie/Language-Detection.git
 3. Create and Activate Virtual Environment (Recommended)
    - python -m venv venv
    - source venv/bin/activate
 4. Install Libraries: pip install numpy pandas scikit-learn
 5. Open `language-detection.ipynb` and run all cells
 6. Or you can download the `language.csv` and `language-detection.ipynb` file from the repository, upload those files to [Google Colab](https://colab.research.google.com/) then run all the cells in the `language-detection.ipynb` Notebook

## Acknowledgments
 - I would like to thank [Aman Kharwal](https://www.linkedin.com/in/aman-kharwal)

## Contact
 - LinkedIn: [Nebeyou Musie](https://www.linkedin.com/in/nebeyou-musie)
 - Gmail: nebeyoumusie@gmail.com
 - Telegram: [Nebeyou Musie](https://t.me/NebeyouMusie)
    
