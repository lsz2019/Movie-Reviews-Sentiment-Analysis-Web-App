# Movie-Reviews-Sentiment-Analyzer
## Using PyTorch and SageMaker

A simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.

## Dataset
[IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)
> Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In _Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies_. Association for Computational Linguistics, 2011.


## Outline
1. Download the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a RNN model.
5. Test the trained model by sending test data to it after deployment.
6. Deploy the model again for the web app
