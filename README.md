# English to French Translation Chatbot

This project explores neural machine translation using Hugging Face transformer models.

The chatbot translates English text into French using the Helsinki-NLP MarianMT model and displays responses with a typing animation for a more interactive experience.

## Features

* English to French translation
* Hugging Face transformer integration
* Interactive chatbot loop
* Typing animation effect
* Real-time text translation

## Technologies Used

* Python
* Hugging Face Transformers
* MarianMT Model
* SentencePiece

## Prerequisites

Before running the chatbot:

* install the required libraries from `requirements.txt`
* ensure Python is installed
* internet connection is required for downloading the Hugging Face model

The translation model used:

```python
Helsinki-NLP/opus-mt-en-fr
```

## Files

* `english-french-translation-chatbot.ipynb`: main notebook
* `requirements.txt`: required libraries

## Sample Translation

Input:

```python
Good morning! How are you today?
```

Output:

```python
Bonjour! Comment allez-vous aujourd'hui?
```

## Learning Outcome

This project helped me explore:

* NLP-based translation
* transformer models
* tokenizer usage
* sequence-to-sequence text generation
* chatbot interaction design

## Future Improvements

* support translation for multiple languages
* add automatic language detection
* store translation history during sessions
* allow file-based text translation
* build a simple GUI using Tkinter
