# IMDB Movie Review Sentiment Analysis

This project demonstrates a simple sentiment analysis model using a Recurrent Neural Network (RNN) built with TensorFlow/Keras. The model is trained on the IMDB dataset to classify movie reviews as either positive or negative.

### Project Overview

The core of this project is a Simple RNN model that learns to understand the sentiment of text data. The dataset consists of 50,000 movie reviews from the Internet Movie Database (IMDB), pre-processed into sequences of integers representing words.

The model architecture is as follows:
- **Embedding Layer**: Converts the integer-encoded words into dense vectors of a fixed size.
- **SimpleRNN Layer**: Processes the sequence of word vectors to capture dependencies.
- **Dense Layer**: A single output neuron with a sigmoid activation function to classify the sentiment (0 for negative, 1 for positive).

### How to Run the Notebook

To run the `DeepLearnin_Notebook1.ipynb` notebook, you need to have Python and Jupyter Notebook installed. You also need to install the necessary libraries.

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

4.  Open the `DeepLearnin_Notebook1.ipynb` file and run the cells in order.

### Results

The model was trained for 10 epochs with early stopping on the validation loss. It achieved a final validation accuracy of approximately 80.66%, which is a solid result for a basic RNN on this task.

Feel free to explore the notebook to see the data loading, pre-processing, model building, training, and prediction steps in detail.
