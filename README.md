# n-gram Counter
This code counts the number of occurrences of each n-gram (a group of n consecutive characters) in a text file.

Usage
To run the code, enter the following command in the terminal:
``python ngramcounter.py``

The code will prompt you to enter the value of n, which specifies the length of the n-grams to generate. The value of n must be between 3 and 6.


# Input
The code will prompt you to enter the value of n, which specifies the length of the n-grams to generate. The value of n must be between 3 and 6.

# Output
The code writes the results to a file called ngramoutput.txt in the same directory as the script. This file will contain a list of n-grams and their counts, sorted in descending order by count. Each n-gram and its count will be on a separate line, with the count followed by a colon and a space, and the n-gram.

For example, if wordlist.txt contains the words "hello" and "world" and n is set to 3, the code will generate the n-grams "hel", "ell", "llo", "wor", "orl", and "rld" and write the following to ngramoutput.txt:

``2: l
2: o
1: d
1: e
1: h
1: l
1: r
1: w``
In this case, the letter "l" appears in two of the n-grams ("ell" and "llo"), so it has a count of 2, and the other letters have a count of 1. You can copy and paste this file to your GitHub repository.



