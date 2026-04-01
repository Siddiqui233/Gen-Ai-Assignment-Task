NLP Chatbot using Hugging Face Transformers
Project Overview

This project implements a console-based conversational chatbot using a pre-trained transformer model from the Hugging Face Model Hub. The chatbot interacts with users in natural language and generates responses dynamically using a transformer-based language model.

The goal of this project is to understand how Natural Language Processing (NLP) models work and how pre-trained transformers can be used to build simple conversational AI systems.

Technologies Used
Python
Hugging Face Transformers
PyTorch
Jupyter Notebook
Model Used

For this project, the chatbot uses the pre-trained model Qwen2.5-0.5B-Instruct from the Hugging Face Model Hub.

This instruction-tuned transformer model can understand prompts and generate conversational responses in natural language.

Features
Interactive chatbot that accepts user input
Uses a pre-trained transformer model
Generates responses dynamically
Maintains conversation flow
Exit option using exit or quit
Project Workflow

The chatbot follows this pipeline:

User Input → Model Processing → Response Generation → Display Output → Loop Until Exit

Workflow steps:

User enters a message.
The tokenizer converts the text into tokens.
The transformer model processes the tokens.
The model generates a response.
The chatbot displays the response.
The conversation continues until the user types exit.
Installation

Clone the repository:

git clone https://github.com/Siddiqui233/Gen-Ai-Assignment-Task.git

Navigate to the project folder:

cd Gen-Ai-Assignment-Task

Install dependencies:

pip install transformers torch
How to Run

Run the notebook in Jupyter Notebook or Google Colab.

Steps:

Open the .ipynb notebook file
Run all cells
Start chatting with the chatbot in the console

Example:

Chatbot: Hello! I am your AI assistant.

User: Hello
Chatbot: Hi there! How can I help you today?

User: What is Artificial Intelligence?
Chatbot: Artificial Intelligence refers to machines that can perform tasks that normally require human intelligence.
Learning Outcomes

Through this project, I learned:

How transformer-based NLP models work
How to load pre-trained models from Hugging Face
How tokenization works in NLP pipelines
How to build an interactive chatbot
How prompt-based text generation works
Author

Majeed Ahmed Siddiqui
Data Science Intern

This project was developed as part of the Data Science Internship program, focusing on Natural Language Processing and building a chatbot using transformer-based models.

GitHub Profile:
https://github.com/Siddiqui233
