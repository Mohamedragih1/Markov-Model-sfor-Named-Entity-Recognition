# Named Entity Recognition Models 

This repository contains implementations of models for the Named Entity Recognition (NER) task. In NER, the goal is to associate words in a sentence with their proper name tags such as person names, organizations, locations, miscellaneous entities, or non-entities.

## Task Description
Given a sentence, the task is to tag each word with one of the following five tags:
- PER (person)
- ORG (organization)
- LOC (location)
- MISC (miscellaneous)
- O (non-entity)

For example, the correct tagging of the sentence "Steve Jobs founded Apple with Steve Wozniak." would be ⟨PER, PER, O, ORG, O, PER, PER⟩. Note that consecutive words constituting a named entity should both be tagged as PER, as in the case of "Steve Jobs".

## Programming Problem 1: Hidden Markov Model (HMM)
In this problem, an implementation of the Hidden Markov Model (HMM) for Named Entity Recognition is provided. The HMM model utilizes the probabilistic nature of sequences to predict the most likely sequence of tags for a given input sentence.



## Programming Problem 2: Max-Entropy Markov Model (MEMM)
In this problem, an implementation of the Max-Entropy Markov Model (MEMM) for Named Entity Recognition is provided. The MEMM model considers the contextual features of words in addition to the sequence information, providing a more sophisticated approach to tagging.



## Instructions for Running the Notebooks
1. Open the respective Colab notebooks linked above.
2. Follow the instructions provided within the notebooks for executing the code.
3. Ensure that all dependencies are installed to run the code successfully.



