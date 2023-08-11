# Final Project: A Deeper Look into spaCy using the US Declaration of Independence 
## Student Name: Alexandra Coffin 
## GitHub Repository: https://github.com/accoffin12/mining_Declaration_Independence
## GitHub Profile: https://github.com/accoffin12 

## CSIS 44610: Web Mining & Applied Natural Language Processing 

# Objective: 

Natural Language Processing (NLP) has evolved over the past decade as algorithms become more powerful. With their use becoming common in daily life, the concern becomes how powerful an NLP is. It has shown to be competent in terms of analyzing basic texts, tweets, and emails. The question is if it has the capability to analyze an older and more complex document. Language has changed since the Colonization of America, and one of the best documents, which still contains Colonial English that is easily accessible, is the Declaration of Independence. 

In this project, I examine the ability of spaCy and NLTK to analyze the 248-year-old documents through multiple processes. With each process serving as the backbone, the results are compared through Sentiment Analysis, Polarity, and a Dependency Parse. 

# Installations & Environment Requirements: 

This notebook requires 3.1x version of python as well as the following Library Installations. To run this notebook, create a separate environment using the following command. If running in VS Code and it asks to set it as workspace folder, select yes. 


    python -m venv .venv 


Once created activate the environment using the following call: 

    .venv\Scripts\activate 

After activated install the following Libraries to use the Notebook. 

* Pip install spacy 

* Python –m spacy download en_core_web_sm 

* Pip install beautifulsoup4 

* Pip install nltk 

# Contents: 

1. Load & Test Needed Modules 
2. Importing the Document & Creating a Pickle 
3. Read the Pickle & Print Test 
4. Creating the Doc Object & Tokenizing 
5. Stop Words part 1 
6. Sentence Detection: 
    6.1: Number of Sentences in the Document 
    6.2: Locating the first word in Sentences 
    6.3: Index Position of Tokens 
7. Attributes for Token Class 
8. Sentiment Analysis & Word Frequency using Tokenization: 
    8.1: Stop Words Part 2: Updates 
    8.2: Polarity 
    8.3: Visualizations 
        8.3.1: The Dependency Parse 
        8.3.2: Graph for Distribution of Sentence Scores by Tokens 

9. Lemmatization 
    9.1: Lemmatization Process 
    9.2: Word Frequency Using Lemmas 
    9.3: Speech Tagging Nouns, Verbs, Adjectives, and Interjection 
    9.4: Name Entity Analysis 
    9.5: Visualizations using Lemmas: 
        9.5.1: Dependency Parsing 
        9.5.2: Unique words 
        9.5.3: Polarity 
        9.5.4: Graph for Distribution of Sentence Scores by Lemmas 
10. Conclusion 

# Methods: 

To execute this project a Transcript of the Declaration of Independence is pulled from the National Archives Page and then pickled. Once picked the data is pulled into an environment and run through two separate types of analysis. 

1. Tokenization 

2. Lemmatization 

  

# Website: https://www.archives.gov/founding-docs/declaration-transcript

# Resources: 

This notebook was created using portions of the following tutorial: 
https://realpython.com/natural-language-processing-spacy-python/

This was used as a base to begin developing the process of analyzing the document as this is an older document and it required a more structured process.  

  
