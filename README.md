# Bhashini Notebook

## Overview
Welcome to my Bhashini notebook! This project focuses on building an end-to-end text-to-speech (TTS) system using the LLM Models provided by Bhashini and ULCA for language processing. The system accepts Hindi text input and generates corresponding speech output through a pipeline architecture. 

## Prerequisites
Before you start, make sure you have the following:
- Python 3.x installed on your system
- The necessary Python libraries, which you can install as outlined below

## Installation
To get everything set up, you'll need to install a couple of libraries. You can do this by running the following commands:

```bash
pip install --force-reinstall typing-extensions==4.5
pip install --force-reinstall openai==1.8
```

## How to Use This Notebook
1. **API Key Setup**:
    - You'll need your OpenAI API key to use the examples in this notebook.
    - Make sure to replace the placeholder (`'sk-###################'`) in the code with your actual API key.

2. **Running the Notebook**:
    - Open `bhashini.ipynb` in Jupyter Notebook or any compatible environment.
    - Execute the cells one by one to see the code in action and understand how it works.

## What's Inside
Here's a quick rundown of what you'll find in the notebook:
1. **Library Installation and Imports**:
    - Commands to install the required libraries.
    - Import statements for all the libraries used in the notebook.

2. **API Configuration**:
    - Instructions on setting up the OpenAI client using your API key.

3. **JSON Handling**:
    - Examples showing how to handle JSON data effectively.

4. **Text-to-Speech Pipeline**:
    - A comprehensive end-to-end pipeline that processes Hindi text, translates it to Punjabi, and generates the corresponding speech output.
    - Utilizes Python for scripting, the requests library for HTTP requests, base64 for audio data encoding, and the wave module for handling WAV audio files.

## Code Highlights
Here are some snippets of the key parts of the notebook:

### Installing Libraries
```python
!pip install --force-reinstall typing-extensions==4.5
!pip install --force-reinstall openai==1.8
```

### Setting Up OpenAI API
```python
from openai import OpenAI
client = OpenAI(api_key = 'sk-###################')
```

### Working with JSON
```python
import json
```

### Text-to-Speech Example
```python
import requests
import base64
import wave

# Example code for converting text to speech
def text_to_speech(text, source_lang='hi', target_lang='pa'):
    # Code to translate text from Hindi to Punjabi
    # Code to convert the translated text to speech
    # Example only, please refer to the notebook for full implementation
    pass
```

## License
This project is licensed under the MIT License. For more details, check out the [LICENSE](LICENSE) file.

## Acknowledgements
A big thank you to OpenAI for providing the awesome API that made this notebook possible, and to Bhashini and ULCA for their powerful language processing models!
