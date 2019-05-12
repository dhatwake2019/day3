# Topic Modeling
[Topic Modeling slides are here](https://docs.google.com/presentation/d/1G0T1b0GZ1U131DWGSALvsooVANUJvAW7XGZRx2KDmQo/edit?usp=sharing)

>A topic model is a simplified representation of a collection of documents. Topic modeling software identifies words with topic labels, such that words that often show up in the same document are more likely to receive the same label. It can identify common subjects in a collection of documents – clusters of words that have similar meanings and associations – and discourse trends over time and across geographical boundaries. This guide will help you use the tool and analyze the results it generates.

>If you’re familiar with the basic idea behind topic modeling, using the tool isn’t difficult. However, you may want to read some background material on topic modeling if you’re not quite sure how it works. Miriam Posner and Andy Wallace’s [Very basic strategies for interpreting results from the Topic Modeling Tool](http://miriamposner.com/blog/very-basic-strategies-for-interpreting-results-from-the-topic-modeling-tool/) is a great starting point for people who think best by doing. (It’s based on a slightly older version of the tool, however.) Ted Underwood’s [Topic modeling made just simple enough](https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/) provides a more theoretical – but still very accessible – introduction to the basic concepts.

*taken from Scott Enderle's [TMT quickstart guide](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html)*

## Data
We'll be using the NC Life History data that we worked with earlier today. 

## Topic Modeling Tool
[Topic Modeling Tool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html) is an open source GUI tool that uses [MALLET](http://mallet.cs.umass.edu/)'s Latent Dirichlet allocation (LDA) implementation.

1. Create a new folder called TMToutput on your Desktop
1. Launch TopicModelingTool.
2. Click 'Input Dir', navigate to the folder of texts, and click (once!) on the folder (do not open the folder). Then select 'Choose'
3. Click 'Output Dir', navigate to the 'TMToutput' folder and click on it (once!) and then click 'Choose'
4. Select the number of topics (20 is probably good here)
4. Click on 'Optional Settings' to take a look at what's there.
5. Wait for a moment while the algorithm runs. It will save the results in your 'TMToutput' folder
6. When the process is done, take a look at the results by opening TMToutput, then output_html, and open all_topics.html. This will open a webpage with all of the topics that have been identified. If you click on one of the topics, you'll see the texts that most closely align with each topic. If you click one one of those, you'll see the text and the topics that are most closely related to it.
7. Spend a few minutes poking around. Also take a look at the output_csv folder and see what's there.

**Sample Outputs**
- [20 topics](http://brandontlocke.com/nc-lifehist20/all_topics.html)
- [40 topics](http://brandontlocke.com/nc-lifehist40/all_topics.html)
- [60 topics](http://brandontlocke.com/nc-lifehist60/all_topics.html)
