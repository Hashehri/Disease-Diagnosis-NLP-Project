### Abstract:

The medical field has become more sophisticated and advanced than it was previously, but early diagnosis of diseases helps reduce the consequences of complications, that's thing inspired us and we recognized some people haven't the ability to know what type of diseases they have, especially at an early stage of diseases. So their cases might become very harmful and very complex, and can not be treated easily. In this project, we will try to help those people who struggle to figure out the kind of pain they feel by providing a simple way that might help them with trusted sources to get ideas about their conditions and how dangerous it is.

### Algorithms:

#### Pre-Process:

1- Text Cleaning:
* Remove english stop words.
* Remove domain specific stop words.
* Lemmatization.
* Remove Entities (POS "Adjictave").
* Remove any digits or special characters.

2- Word Embbeding:
* Count Vectorizer Without grams.
* TF-IDF Without grams.

#### Topic Modeling (step 1):
* LSA
* LDA
* CorEx
***we used cosine similarity in order to find a similar topic to the new user input*** 

#### Classification:

Using separated LogisticRegreassion model for each human body organ system to perform the disease prediction.


### Data:

In order to achieve the project objective, we will use one of the trusted books in the field and one of that books is "Professional Guide to Diseases 11th edition". The book contains over 2900 pages that will be used as a source/reference for this project and all necessary information will be extended from it.


### Tools:
* Data manipulation and cleaning: Pandas and Numpy, Matplotlib
* Data Storing: Sqlite3 and pickle
* Text precossing: NLTK, spaCy, gensim, scikit-learn , pyPDF2
* Topic Modeling: LSA (Non-negative Matrix factorization), LDA (Latent Derilicht Analysis), CorEx 
* Visualization: Tableau, matplotlib, seaborn

Communication: 

The project presnted in [slides ]()




