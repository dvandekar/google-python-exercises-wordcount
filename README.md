## google-python-exercises-wordcount
Google Python Exercises Wordcount Module

### Summary

This repository contains one possible solution to the Google Python Basic Exercise entitled Wordcount.py. This program was written using Python version 2.7.11.

### Description

This Python script will perform a word count on a text file specified in the command line argument, print the results to the terminal, and export a csv file of the results to the active directory. Non-alpha characters are stripped from the file and case is ignored. The count function returns each word and the number of occurences sorted alphabeticaly. The top count function returns the top 20 words and the number of occurences sorted in descending order. In both cases the complete result set is exported to a csv file in the directory.

### Usage

To use this program launch a terminal or command line window such as PowerShell and navigate to the target directory. The script and the target text file should be in the same directory when run. Enter the following command: *./wordcount.py {--count | --topcount} file*

* **./wordcount.py** is the program name and execution argument
* **--count** will return each word sorted alphabetically *OR* **--topcount** will return the top 20 results sorted by occurence in descending order
* **file** will be the name of the file the wordcount is being performed on including the file extension

### Future Enhancement Ideas

* Allow user to specify directory for target file
* Allow user to specify save location for csv file
* Generate a word cloud from the source file
* ...
