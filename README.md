
# Email Classifier

## Overview
The **Email Classifier** is a machine learning-based project that automatically categorises emails into predefined classes such as spam, promotions, social, and important messages. This project aims to enhance email organization and filter out unwanted messages efficiently.

## Features
- Automatically classifies emails based on their content.
- Uses Natural Language Processing (NLP) techniques.
- Supports two classification(spam, non-spam)
- Implements Support vector Classifier for email classification.
- Can be integrated into email services or used as a standalone classifier.

## Technologies Used
- Python
- Scikit-learn
- Natural Language Toolkit (NLTK)
- Pandas
- NumPy
- Jupyter Notebook (for experimentation and visualization)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/email-classifier.git
   cd email-classifier
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv env
   source env/bin/activate   # On Windows use: env\Scripts\activate
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Dataset
The model is trained on a labelled dataset containing email content and their respective classifications. You can use publicly available datasets such as:
- Enron Email Dataset
- SpamAssassin Dataset

## Model Training
The project utilizes a machine-learning pipeline that includes:
- Text preprocessing (tokenization, stopword removal, stemming)
- Feature extraction using TF-IDF vectorization
- Classification using models like Naive Bayes, Logistic Regression, or SVC
- Evaluation using accuracy, precision, recall, and F1-score

## Contributing
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your branch and create a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
For any queries, feel free to reach out via 'kr.amanjha02@gmail.com' or open an issue in the repository.

---
*Happy Coding!* 🚀

