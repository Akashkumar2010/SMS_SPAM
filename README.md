## SMS Spam Detection

## Project Description

This project aims to build a machine learning model to detect spam messages in SMS text data. By utilizing various Natural Language Processing (NLP) techniques and the Naive Bayes classifier, the model predicts whether a given message is spam or ham (not spam).

## Dataset

The dataset used in this project consists of SMS messages labeled as "spam" or "ham":
- **v1**: Label indicating whether the message is spam or ham.
- **v2**: The text of the SMS message.

The dataset has been preprocessed to handle missing values and encode text data.

## Key Features of the Dataset
- A total of 5,572 messages with corresponding labels.
- The data has been cleaned and tokenized using NLP techniques like stemming, lemmatization, and removal of stop words.

## Project Steps
1. **Data Loading**: The dataset is loaded and examined for missing values or errors.
2. **Text Preprocessing**: Includes steps like tokenization, stop word removal, and lemmatization.
3. **Feature Extraction**: Text data is converted into numerical features using techniques like Count Vectorization and TF-IDF.
4. **Model Training**: A Naive Bayes classifier is trained on the extracted features.
5. **Evaluation**: The model is evaluated using accuracy, confusion matrix, and classification report metrics.

## Installation and Usage

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
3. Run the notebook using Jupyter:
    ```sh
    jupyter notebook sms_spam.ipynb
    ```

## Results
The notebook provides an analysis of the model's performance, including its accuracy, precision, recall, and F1-score. 

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
