# Question Generation Model

This project creates a question generation model using the Hugging Face Transformers library and provides a user-friendly interface with the Gradio interface.

## Project Summary

This project automatically generates questions from text using the `google/byt5-small` model. With the Gradio interface, users can enter text and have the model generate questions.

## Features

- **Question Generation:** Generates questions based on given text.
- **Gradio Interface:** Allows users to enter text and easily view results.
- **Hugging Face Integration:** The model and tokenizer are loaded and run using the Hugging Face library.

## Usage

### Requirements

- Python 3.7 or later
- `transformers` library
- `torch` library
- `gradio` library

## Dataset Used

In this project, the [Turkish MMLU: The Most Comprehensive and Original Turkish Dataset for Artificial Intelligence and Academic Applications](https://doi.org/10.5281/zenodo.13378019) dataset was used. The owner of the dataset is M. Ali Bayram and published by Zenodo. Within the scope of the project, this dataset was used to train the model for automatically generating questions from texts.

For more information about the dataset, you can visit [this link](https://doi.org/10.5281/zenodo.13378019).




