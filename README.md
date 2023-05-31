# Question Answering Model

This code implements a question-answering (QA) model using a Bag-of-Words (BOW) algorithm. It leverages the NLTK library for text preprocessing and scikit-learn for machine learning components. The model takes in user questions and returns the most relevant answer from a dataset of pre-defined questions and answers.

This code is inspired by the guide available at [https://www.kaggle.com/code/omgamici/interactive-question-answer-model](https://www.kaggle.com/code/omgamici/interactive-question-answer-model), and the dataset used can be found at [https://www.kaggle.com/datasets/rtatman/questionanswer-dataset?resource=download](https://www.kaggle.com/datasets/rtatman/questionanswer-dataset?resource=download).

## Dependencies

Make sure you have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- NLTK (Natural Language Toolkit)
- scikit-learn

You can install the required Python libraries using pip:

```
pip install pandas numpy nltk scikit-learn
```
# Dataset

The model uses a dataset of questions and answers to provide responses. The dataset used can be downloaded from <a href="https://www.kaggle.com/datasets/rtatman/questionanswer-dataset?resource=download"> here</a>.

The dataset should be stored in the following structure:

- S08_question_answer_pairs.txt
- S09_question_answer_pairs.txt
- S10_question_answer_pairs.txt

# Usage

1. Clone or download the code from the repository.
2. Ensure that the dataset files 
 `(S08_question_answer_pairs.txt`,
 `S09_question_answer_pairs.txt`, 
 `S10_question_answer_pairs.txt`) are stored in the `dataset` directory within the code directory.
3. Install the required dependencies as mentioned in the "Dependencies" section.
4. Run the code using a Python interpreter:
 ```python qa_model.py```
5. Input your question and press enter to get the corresponding answer.

# Customization
- If you have a different dataset, you can modify the code to read your dataset files by updating the file paths in the code.
- You can modify the text preprocessing steps in the code to suit your requirements.
- Feel free to experiment with different machine learning algorithms or models for question-answering.

# License

This code is released under the <a href="https://github.com/emmystringzhs/machine_learning/blob/main/LICENSE">MIT License.</a>
