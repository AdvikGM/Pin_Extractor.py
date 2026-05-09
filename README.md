Pin Extractor
A simple Python project that extracts secret PIN codes from poems using word lengths.
How It Works

Each line of a poem contains one hidden digit.

The program:
Splits the poem into lines
Splits each line into words
Takes the nth word from the nth line
Finds the length of that word
Adds the length to a secret code
If a line does not contain enough words, the program adds 0 instead.

Example
Poem
Stars and the moonshine in the skywhite and until the end of the night
Extracted PIN
4320

Features


Works with multiple poems


Uses:
functions
loops
lists
enumerate
conditions
string methods

Code Example
print(pin_extractor([poem, poem2, poem3]))

Output
['4320', '5536', '50000']

What I Learned
Python functions
Loops and indexing
String splitting
Error handling with conditions
Lists and list appending

Author
AdvikGM 🚀
