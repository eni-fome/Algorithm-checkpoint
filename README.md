# Sentence Analysis Project

This project involves the development of an algorithm that reads a sentence character by character, determining various characteristics such as the length of the sentence, the number of words, and the number of vowels.

## Algorithm Overview

The algorithm operates on the following principles:

1. **Length Calculation:**
   - Iterates through each character in the sentence.
   - Increments a counter for each character, determining the length of the sentence.

2. **Word Count:**
   - Identifies words based on spaces between characters.
   - Increments a counter for each space encountered.

3. **Vowel Count:**
   - Determines the number of vowels (assuming English vowels) in the sentence.
   - Increments a counter for each vowel encountered.

4. **Loop Termination:**
   - The loop continues until a point is encountered, signifying the end of the sentence.

## Usage

The algorithm is designed to be flexible and can be integrated into various applications or scripts.

1. **ReadCharacter() Function:**
   - The algorithm assumes the existence of a function `ReadCharacter()` to read one character at a time.

2. **Output:**
   - The results, including the length of the sentence, the number of words, and the number of vowels, are displayed as output.

## How to Run

1. **Environment Setup:**
   - Ensure you have an environment where the algorithm can be executed.

2. **Integrate ReadCharacter() Function:**
   - Implement the `ReadCharacter()` function or adapt the algorithm to read characters from your input source.

3. **Run the Algorithm:**
   - Execute the algorithm, and it will process the input sentence and provide the desired statistics.

## Example

For a sentence "This is a sample sentence.", the algorithm would output:
