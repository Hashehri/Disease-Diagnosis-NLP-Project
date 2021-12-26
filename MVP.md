
## Data Extraction by Using PyPDF4 Framework:

After we defined the target book that going to be used in the project and got a digital copy in pdf format. We performed the pdf extraction methodology, in order to extract each disease from the book with specified all Causes, Signs, Diagnosis, Complications, and Pathophysiology on each disease, and split them into lists.

**As result, we got 20,834 words in one chapter out of 20 chapters.**

* **Notice:**

<br />

**We used one chapter as an experimental test, and then we will apply the same techniques and methodology that were used in the experimental stage in the rest of the book chapters.**


## Pre-processing:

In this stage and after extracting the data from the book, we will perform some pre-processing techniques that are commonly used in NLP.

pre-processing techniques:
* Tokenization: To create a bag-of-words.
* Lowercasing: Convert the words to lower case.
* Stemming: Shorten words to their root.
* Removing stop-words, unwanted tokens, and punctuations.
* CountVectorizer: Convert the documents into word matrics.

