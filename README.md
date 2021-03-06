# Coding_Exercise

Using C++, write a program to do the following:

1. Open a file specified as the first parameter on the command-line that contains a list of filenames, one filename per line.

2. For each filename in the list, read each file and tokenize the contents.
  a. Tokenizing for this problem is defined as separating the file into words (characters delimited by whitespace), stripping leading and trailing punctuation, and forcing the token to be lowercase.

3. Output a file specified by the second parameter on the command line containing a list of total unique tokens and their count, each on a separate line, sorted by frequency.

For instance, if the first file (input.txt) contained a single line: test.txt

And that file contained the text: `This is only a test. A *very* short test!`

### Running the program:

> ./counter input.txt output.txt

Would result in an output file (output.txt) that looks like:
```
a 2
test 2
is 1
only 1
short 1
this 1
very 1
```
You can use STL, but avoid usage of third-party libraries. Note that although the above example is frequency and alphabetically sorted, only frequency sorting is required. For purposes of this problem, you can assume all valid input files will be UTF8 encoded English text.
Use Doxygen-style function documentation.

You should approach this project as you would if you worked at Cricut in terms of quality, style,
and performance.


### Contents

###### main.cpp (main c++ file)
###### main.exe (main compiled executable)
###### input.txt (contains list of text files to load into program)
###### test files (contain text to read from)

