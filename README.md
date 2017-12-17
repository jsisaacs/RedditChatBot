# RedditChatBot

I used the TensorFlow Neural Machine Translation model trained with all the Reddit comments from November 2017. Here is an example of an interaction:

![Chatbot Interaction](https://i.imgur.com/7UobrZB.png)

As you can see, it doesn't really work that well. I trained the model on a Paperspace VM that had 30 GB of RAM and a Quatro M4000 GPU for roughly 60k iterations. I didn't get it to a full epoch because of cost and training time, but I believe that it would have had an improvement in the chatbot's performance. The [dataset](http://files.pushshift.io/reddit/comments/) was roughly 10 GB zipped and 60GB unzipped.

Here is what the TensorBoard's Embedding Projector looks like:

![Embedding Projector](https://i.imgur.com/D4n8kTI.png)
