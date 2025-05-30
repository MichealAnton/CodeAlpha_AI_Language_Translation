# CodeAlpha_AI_Language_Translation
## Overview
This is a simple translation tool built with Python that provides a user-friendly interface in a Jupyter notebook environment. The tool uses the Google Translate API (via the googletrans library) to translate text between multiple languages.

## Features
Translate text between 10+ languages

Automatic language detection

Clean, interactive user interface

Real-time translation results

Displays original and translated text with language codes

## Supported Languages
Auto Detect

English

Spanish

French

German

Japanese

Russian

Chinese

Arabic

Hindi

Portuguese

## Requirements
Python 3.x

Jupyter Notebook

googletrans==4.0.0-rc1

ipywidgets

## Installation
Clone this repository or copy the code into a Jupyter notebook

Install the required packages:

 ```bash
pip install googletrans==4.0.0-rc1
pip install ipywidgets
 ```
## Usage
Run the code in a Jupyter notebook cell

Enter the text you want to translate in the input box

Select the source language (or leave as "Auto Detect")

Select the target language

Click the "Translate" button

View the translation results below the button


## Notes
The tool requires an internet connection to access the Google Translate API

For large volumes of translation, consider using the official Google Cloud Translation API

The auto-detection feature may not be 100% accurate with very short texts
