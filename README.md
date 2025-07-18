# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: KABILAN M

*INTERN ID*: CT04CH1571

*DOMAIN*: PYTHON

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH




###  **Task Description: Text Classification using Naive Bayes **

####  **Objective:**

The main goal of this task is to build a **machine learning model** that can **classify text data** using the **Naive Bayes algorithm**. This is a common application in **Natural Language Processing (NLP)**, especially for tasks like spam detection, sentiment analysis, or topic classification.


###  **Tools and Libraries Used:**

* `pandas` – for data handling
* `sklearn.model_selection` – for train-test splitting
* `sklearn.feature_extraction.text` – to convert text into numerical format (vectorization)
* `sklearn.naive_bayes` – to apply the Naive Bayes classification algorithm
* `sklearn.metrics` – for evaluating model accuracy
* `seaborn` – for visualizing the confusion matrix


###  **Key Steps in the Task:**

1. **Data Loading**:

   * A CSV or text dataset (likely containing text samples and their corresponding labels) is loaded using `pandas`.

2. **Text Vectorization**:

   * The text data is transformed into numeric features using **CountVectorizer** or **TfidfVectorizer**, so the machine learning algorithm can understand it.

3. **Train-Test Split**:

   * The dataset is split into **training** and **testing sets** using `train_test_split`.

4. **Model Training**:

   * A **Naive Bayes classifier** (typically `MultinomialNB`) is trained on the training data.

5. **Prediction and Evaluation**:

   * The model predicts labels on the test set.
   * Performance is evaluated using:

     * **Accuracy Score**
     * **Confusion Matrix**
     * **Classification Report**

6. **Visualization**:

   * The confusion matrix is visualized using **Seaborn’s heatmap**, providing a visual breakdown of true/false predictions.


###  **Expected Outcome:**

By the end of the task, you should have:

* A trained Naive Bayes model that can classify text
* Evaluation metrics showing how well it performs
* A confusion matrix heatmap showing the distribution of prediction accuracy


###  **Use Cases:**

This task is relevant to:

* Spam detection
* Sentiment analysis
* Document/topic classification
* Chatbots and customer support ticket triaging

##OUTPUT:
