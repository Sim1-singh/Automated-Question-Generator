
# Automated Question Generation using NLP Techniques

This repository contains the code and resources used for the project on generating assessment questions from textual content using state-of-the-art Natural Language Processing (NLP) techniques.

## Overview

The course explores various NLP methods to automate the creation of different types of assessment questions, including:
- Multiple Choice Questions (MCQs)
- True/False Questions
- Fill-in-the-blanks
- Match the Following

We utilize a variety of NLP tools and models, ranging from traditional word vectors to cutting-edge transformers like BERT, GPT-2, and T5.

## Project Outline

### 1. Generate Distractors for MCQs
- **Objective:** Automatically generate plausible incorrect answers for MCQs.
- **Tools:** WordNet, ConceptNet, Sense2vec.

### 2. Generate True/False Questions
- **Objective:** Convert text into True/False questions by altering the sentence endings.
- **Tools:** Sentence BERT, Constituency Parser (AllenNLP), GPT-2.

### 3. Generate MCQs
- **Objective:** Train a T5 transformer to generate MCQs from any text content.
- **Tools:** HuggingFace Transformers, Pytorch Lightning.

### 4. Generate Fill-in-the-Blanks Questions
- **Objective:** Identify key phrases in the text and turn them into blanks.
- **Tools:** Python Keyword Extraction, FlashText, HTML ElementTree (for visualization).

### 5. Generate Match the Following Questions
- **Objective:** Create matching-type questions by extracting and pairing keywords.
- **Tools:** Python Keyword Extraction, FlashText, BERT (for word sense disambiguation).

## Getting Started

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/nlp-question-generation.git
   cd nlp-question-generation
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks
Each section of the course is accompanied by a Google Colab notebook. Open the notebooks in Google Colab to explore the code and run the models on free cloud GPUs provided by Google.

### Examples
Check the `/notebooks` directory for example notebooks corresponding to each section of the course.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---

This structure provides a clear overview of the project, prerequisites, and instructions, making it easy for users to understand and get started with your course.
