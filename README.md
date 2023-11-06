# Flash Card App

A language learning tool that utilizes flashcards to help users memorize words in a foreign language, such as French. This application presents a word in French and allows the user to flip the card to see the English translation.

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Developer](#developer)

## Introduction

This Flash Card App is a graphical user interface application developed with Python and Tkinter. It's designed to make language learning more interactive and engaging.

## Technologies

- Python 3.8+
- Tkinter
- Pandas

## Features

- Interactive flashcards displaying French to English translations.
- Ability to mark words as 'known' which removes them from the rotation.
- Randomized words to ensure diverse learning material.
- Simple and elegant UI for a distraction-free learning environment.

## Setup

To run this app, you'll need Python and the required libraries installed on your system. Follow the steps below:

1. Make sure you have Python installed on your machine. If not, download and install it from [python.org](https://www.python.org/downloads/).
2. Install Pandas library using pip if you haven't already:
   ```shell
   pip install pandas
    ```
Clone or download this repository to your local machine.
Ensure you have the following files in the data directory:
french_words.csv for the original dataset.
words_to_learn.csv for words that are being learned (this file will be created after the first run).

## Usage
To use the Flash Card App:

Run main.py to start the application.
The app will display a French word, wait for you to recall the English translation, and then you can flip the card to check your answer.
If you knew the word, click the right button to mark it as known, and it won't be shown again.
If you didn't know the word, click the wrong button to skip, and it will be shown again later.
The progress of your learning will be saved in words_to_learn.csv.

## Developer
Developed by Ali Jafarbeglou. For any queries or suggestions, feel free to contact.


Please ensure that your `data/french_words.csv` is present in the `data` directory of your project. The images such as `card_front.png`, `card_back.png`, `wrong.png`, and `right.png` should be in an `images` directory within your project for the application to run correctly.


