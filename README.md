# SIT RESEARCH

GPU = RTX 3060 (12GB)

Dataset <br>
<a href="https://huggingface.co/datasets/amazon_us_reviews">Amazon US Reviews</a>
<br>
![Alt text](/Result/Result-Amazon.png "Result of Amazon Dataset")
<br>
Epoch = 10, 10k rows, 1e-5 lr, 15% test size <br>
The result of Amazon Dataset shows that BERT-RCNN is the best for the precision, but for the other metrics (accuracy, F1-Score, and Time) Bert-Base shows the best

For the GPT pairing, GPT-RCNN shows the best result in every aspect

For the BERT-GPT shows pretty high precision score, but for the other metrics. Put the GPT first in the first layer shows better result
<br>
<br>
<a href="https://huggingface.co/datasets/imdb">IMDB</a>
<br>
My target is to compete with the other model in this leaderboard of combining BERT-GPT for doing sentiment analysis task with several methodology in fine-tuning. <a href="https://paperswithcode.com/sota/sentiment-analysis-on-imdb">Papers With Code Leaderboard Models</a> <br>

![Alt text](/Result/Result-IMDB.png "Result of IMDB Dataset")

