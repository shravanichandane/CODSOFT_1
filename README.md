# TASK 1

# Movie Genre Classification Project

## Overview:
This project aims to classify movie genres based on their descriptions using natural language processing techniques and machine learning algorithms. The steps involved in the project are outlined below.

### Dataset:
You can get the Dataset [HERE](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb).

### Code:
You can get the code [HERE](https://github.com/shravanichandane/CODSOFT_1/blob/main/CODSOFT_1.ipynb)

### Step-by-Step Pla- Validation accuracy: Approximately 58.25%
- Performance varies across genres:
  - High precision, recall, and F1-scores for comedy, documentary, drama, and horror.
  - Poor performance for genres like biography, fantasy, music, mystery, and romance.
- Challenges affecting model performance:
  - Limited representation of some genres.
  - Overlapping characteristics among genres.
  - Imbalanced class distribution in the dataset.
- Suggestions for improvement:
  - Balancing the dataset by collecting more data for underrepresented genres.
  - Incorporating additional features besides descriptions.
  - Experimenting with different machine learning algorithms or ensemble methods.
  - Fine-tuning model hyperparameters and text preprocessing techniques.
- Overall, the model shows promise but requires further refinement to enhance performance across all genres.:
#### 1. Extract Data:

* Unzip the provided training and testing data files.
* Read the data into pandas DataFrames.

#### 2. EDA and Data Visualization:

* Explore the data distribution.
* Visualize the most frequent words in descriptions.
* Visualize the distribution of movie genres with enhanced aesthetics.
  
#### 3. Preprocess Data:

* Clean and preprocess the text data (description).
* Convert text data into numerical features using techniques like TF-IDF.
* Add advanced text preprocessing (removing special characters, stemming/lemmatization).

#### 4. Build and Evaluate the Model:

* Train the Logistic Regression model.
* Evaluate the model using accuracy and classification report.

#### 5. Make Predictions:

* Use the trained model to predict genres for the test data.

#### 6. Visualize Results:

* Display model evaluation metrics.
* Show a sample of predictions from the test set.

### Conclusion:

- Validation accuracy: Approximately 58.25%
- Performance varies across genres:
  - High precision, recall, and F1-scores for comedy, documentary, drama, and horror.
  - Poor performance for genres like biography, fantasy, music, mystery, and romance.
- Challenges affecting model performance:
  - Limited representation of some genres.
  - Overlapping characteristics among genres.
  - Imbalanced class distribution in the dataset.
- Suggestions for improvement:
  - Balancing the dataset by collecting more data for underrepresented genres.
  - Incorporating additional features besides descriptions.
  - Experimenting with different machine learning algorithms or ensemble methods.
  - Fine-tuning model hyperparameters and text preprocessing techniques.
- Overall, the model shows promise but requires further refinement to enhance performance across all genres.
