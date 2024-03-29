# Topic Modeling
This is a kind of technique in which analyzes and manipulates a huge Text Corpus. It gathers together all the topics which are hidden in the various documents inside that text corpus. Hence grouping together documents w.r.t. topics.

Important to note that, we cannot apply Supervised Learning on it to get a Machine Learning Model. As for doing that, we would need to have historical data available, on which to train the model. In real-life assignments, you won't have that liberty that you would be given historical records to train on, instead the data will be in raw format, and will be at your perusal, as to how you would go about it. 

Obviously, if the historical data would have been available, the task would be a lot easier.
So, Topic Modeling in our article, isn't about Supervised Learing.

We get text-corpus in our daily life. A machine is unable to determine whether the text is of positive nature or negative. Or if we are getting emails, then whether it is a spam email or a legitimate (ham) email. 

In reality, the text received by a machine can have N number of Labels.

For example, if there's an article from the news paper, then it will be without any Label (Negative or Positive) initially. So being Data Scientists, it will be our job to determine the nature of the text, using the Topic Modeling technique and to conclude what is it's kind. 

So what Topic Modeling does is, it divides a text corpus (i.e. documents inside that text corpus) into multiple topics and provides us the probablity representation of each topic inside documents. 

It also provides us the probablity of Words found in any perticular topic w.r.t. to all documents. 

- [Main Page](README.md)
- [What is Latent Dirichlet Allocation](lda.md)
