# sentiment-analysis
 An attempt at sentiment analysis

Prerequisites:

python -m pip install scipy
pip install -U scikit-learn
pip install transformers
pip install numpy
pip install pandas
pip install tensorflow (Based on your PC specifications, refer to website for more details: https://www.tensorflow.org/install/pip)
PyTorch(Based on your PC specifications, refer to website for more details: https://pytorch.org/get-started/locally/)

Instructions:
Name the input csv as test.csv with the columns text, expected_sentiment
Place within the same directory as test.ipynb
Run the notebook
Output is be a file labelled output_sentiment_test.csv with the columns text, expected_sentiment, model_output, confidence_score

Sources:
https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset
https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest