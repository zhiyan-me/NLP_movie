## Terms 
The project is to be conducted in groups of two.
Date for the final submission : 17th of January

## Corpus
The imdb corpus from huggingface : stanfordnlp/imdb. 

## Goal
We want to see what is the general opinion on actors and actresses in the imdb corpus. 

## How
### import data

### entity taggers
Try different named entity taggers and chose the one you think fit best the problem. You will chose one and motivate your choice.
1) What is entity tagger?
 designed to identify and classify specific entities within a text. These entities can represent people, organizations, locations, dates, quantities, and other predefined categories. The process is commonly referred to as Named Entity Recognition (NER) or Entity Tagging.
2) example 

3) NER test

4) NER evaluation 
explain how and why

### sentiment analysis
Try and test different sentiment analysis models. Include nltk and gensim sentiment analysis models as baselines. Chose one and motivate your choice.
1) models
gensim , nltk

2) evaluation

### split and index given person name
Split the corpus in sentences and index them given the persons they carry.
### score
Build a score that gives an idea of the opinion of every person over the entire corpus.
### rank
Rank the persons given the opinion found in the corpus.
### best represent sentence
Find the sentence(s) that represent the best a person (could be considered as the most central sentence(s) among the sentences that carry that person.

## Deliverables
A video that presents and explains the work
A csv file with the opinion score for every person in the corpus
A summary of the choices made, the motivation of those choices, the algorithms and scores used, and the project pipeline.
