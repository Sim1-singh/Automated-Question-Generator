# Automated-Question-Generator using NLP
This repository contains the code and resources used for a project on generating assessment questions from textual content using state-of-the-art Natural Language Processing (NLP) techniques.
Overview
The course explores various NLP methods to automate the creation of different types of assessment questions, including:

Multiple Choice Questions (MCQs)
True/False Questions
Fill-in-the-blanks
Match the Following
We utilize a variety of NLP tools and models, ranging from traditional word vectors to cutting-edge transformers like BERT, GPT-2, and T5.
# Project Outline
1. Generate Distractors for MCQs
Objective: Automatically generate plausible incorrect answers for MCQs.
Tools: WordNet, ConceptNet, Sense2vec.
2. Generate True/False Questions
Objective: Convert text into True/False questions by altering the sentence endings.
Tools: Sentence BERT, Constituency Parser (AllenNLP), GPT-2.
3. Generate MCQs
Objective: Train a T5 transformer to generate MCQs from any text content.
Tools: HuggingFace Transformers, Pytorch Lightning.
4. Generate Fill-in-the-Blanks Questions
Objective: Identify key phrases in the text and turn them into blanks.
Tools: Python Keyword Extraction, FlashText, HTML ElementTree (for visualization).
5. Generate Match the Following Questions
Objective: Create matching-type questions by extracting and pairing keywords.
Tools: Python Keyword Extraction, FlashText, BERT (for word sense disambiguation).
