# Text Summarization
### WCN — Weighted Contextual N-gram method for evaluation of Text Summarization

In this project, I fine tune T5 model on Extreme Summarization (XSum) Dataset achieveing a rouge2 f score of <b>9.5%</b> on test data. Further I discuss the drawbacks of ngram based metrics as well as contextual word metrics. 

Finally, I propose use of <i> Weighted Contextual N-gram (WCN)</i> method – an alternative metric which can be more effective for evaluation of text generation tasks.

The complete documentation of the project can be found [here](https://github.com/Aditya-shahh/Text_Summarization/blob/main/Text_summarization.pdf)

### Dataset

I use the Extreme Summarization (XSum) Dataset. The dataset can be downloaded from [here](https://drive.google.com/file/d/1thjRlmbgwlCBDnHIuwWprG7T9S7_tAZl/view?usp=sharing)

The dataset consists of BBC articles and accompanying single sentence summaries. Specifically, each article is prefaced with an introductory sentence (aka summary) which is professionally written, typically by the author
of the article. 

There are two features in this dataset:<br> 
(1) document: Input news article. <br>
(2) summary: Onesentence summary of the article. <br>

The idea is to generate a short, one-sentence news summary
answering the question ”What is the article about?”. There are in total 226k samples: 204,045 samples for training data, 11,332 samples for validation data and 11,334 samples for test data. The average number of words in a document is 431.07 (19.77 sentences) and the average number of
words in a summary is 23.26.


### Code
The source code for this project can be found at ```text_summarization.ipynb```. 
