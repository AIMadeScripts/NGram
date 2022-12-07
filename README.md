# ngram-counter
This is a simple Python script that counts the frequency of n-grams in a given word list. The script reads the words from a text file and outputs the counts of n-grams to another text file.

Usage
To use this script, you need to have Python installed on your system. The script has been tested with Python 3.5 and above, but should work with any recent version of Python.

First, download the ngram-counter.py script and save it to a convenient location on your system. Then, create a text file containing the words that you want to count the n-grams for. The words should be separated by newline characters. Save this file as wordlist.txt in the same directory as the ngram-counter.py script.

Next, open a terminal or command prompt and navigate to the directory where you saved the script and wordlist.txt file. Run the following command to execute the script:

python ngram-counter.py
This will run the script and generate an output file named ngramoutput.txt in the same directory. This file will contain the counts of n-grams, with each n-gram and its count on a separate line. The n-grams will be sorted in descending order by their counts.

You can also specify the minimum and maximum values of n to use when generating the n-grams. For example, to only generate 3-grams and 4-grams, you can use the following command:

python ngram-counter.py -n 3 -x 4
Options
The ngram-counter.py script supports the following options:

-n, --min_n: The minimum value of n to use when generating n-grams (default: 3)
-x, --max_n: The maximum value of n to use when generating n-grams (default: 6)
Example
To demonstrate the usage of this script, let's say we have the following wordlist.txt file:

cat
dog
elephant
bird
Running the ngram-counter.py script with the default values will produce the following ngramoutput.txt file:

3: cat
2: dog
1: ele
1: pha
1: ant
1: bir
1: rd
As you can see, the script has counted the 3-grams (trigrams) in the wordlist.txt file and sorted them in descending order by their counts.

Conclusion
This simple script can be useful for counting the frequency of n-grams in a given word list. It is easy to use and customize, and can be extended for more advanced applications.
