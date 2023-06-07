# Text Sentiment Analysis Deep Learning

This repository contains code for performing text sentiment analysis using deep learning techniques. It utilizes the BERT (Bidirectional Encoder Representations from Transformers) model for sentiment classification. The code is based on the following tutorial: [Text Classification with BERT in PyTorch](https://towardsdatascience.com/text-classification-with-bert-in-pytorch-887965e5820f).

## Installation

Before running the code, make sure to install the required dependencies by running the following commands:

```
!pip install nlpaug
!pip install transformers
```

Additionally, the code requires downloading the NLTK tokenizer. You can download it by running the following code:

```python
import nltk
nltk.download('punkt')
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/armansouri9/Text-sentiment-analysis-deep-learning.git
```

2. Navigate to the repository directory:

```bash
cd Text-sentiment-analysis-deep-learning
```

3. Open the Jupyter Notebook file named `text_sentiment_analysis.ipynb` in Jupyter Notebook or any compatible environment.

4. Follow the instructions and run the code cells to perform text sentiment analysis using the BERT model.

Note: The code assumes that you have a CSV file named `data.csv` containing the text data for sentiment analysis. Make sure to update the file path accordingly in the code.

## License

This project is licensed under a Free License.
