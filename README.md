# Flash card project
Flash card project is a simple Python-based application built with Tkinter that helps users learn and memorize vocabulary using flashcards. It presents users with a French word, allows them to guess the English translation, and then reveals the correct answer.

## Description

Flash card projectis designed to enhance language learning through interactive flashcards. It can be used for studying French or adapted for other languages. The application reads flashcard data from a CSV file, and users can mark words they know, moving them to a separate list for further practice.

## Quick Start

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Flash-card-project.git
    cd flash-card-project
    ```

2. Install the required dependencies:

    ```bash
    pip install pandas
    ```

3. Run the application:

    ```bash
    python flash_card_project.py
    ```

## Usage

- Upon launching the application, a flashcard with a French word is displayed.
- Attempt to guess the English translation.
- Click on the checkmark if you know the word, or the 'X' if you don't.
- The known words are moved to a separate list for further practice.
- Continue learning and practicing until all words are known.

Feel free to customize the flashcards by modifying the `data/french_words.csv` file with your own vocabulary.
