# Introduction
A text file needs to be replaced from all possible words in English to French. I have chosen Python as programming language to make a text translator with the given dictionary. 

## Library Used
With the use of pandas library I have made a word translator as pandas library offers multiple functions.

Pandas is a software library written for the Python programming language for data manipulation and analysis.

## Concept Used
I have used the concept of hashing to minimize the time complexity. 

Hashing is the transformation of a string of characters into a usually shorter fixed-length value or key that represents the original string. Hashing is used to index and retrieve items in a database because it is faster to find the item using the shorter hashed key than to find it using the original value.


## What it Does?

1.	Find an English to French dictionary(french_dictionary.csv).
2.	Read the text file, replace words and dictionary.
3.	Find all words that in the replace words list that has a replacement in the dictionary.
4.	Replace the words in the text file.
5.	save the processed file(check.txt).

## Output
The Output in which the translated file is saved is check.txt. The program file is Word_translate.ipynb.

1.	Unique list of words that was replaced with French words from the dictionary - 996 is the total number of Unique words
2.	Number of times a word was replace - It is shown in the program in Word_translate.ipynb.
a.	Frequency of each word replaced - It is shown in the program in Word_translate.ipynb.
3.	Accuracy of the replace in terms of all occurrences, casing and special characters to be maintained accurately - All the words have been replaced that were given in the dictionary.
4.	Time taken to process - 00:05 seconds
5.	Memory taken to process - 106086400 bytes or 106 Mb.

