# Notes on Text Analysis using NLTK
[Primer on text analysis/visualization from Jeffrey Heer at the University of Washington](https://courses.cs.washington.edu/courses/cse512/15sp/lectures/CSE512-Text.pdf)
## Why would you use different text analysis functions?
### Concordance 
- To see how a word is used
- To see how often a word is used
- To see the contexts in which a word is used

The *number of returns* for the concordance tells you *how many times* the a term is used in a text. A concordance *provides context* for a term by listing the term with a specified number of words on either side. 

Concordance information: https://slcladal.github.io/kwics.html

### Similar (aka "Word Similarity")
- To see what other words appear in similar contexts
- Provides a slightly different lense on context than "concordance."

Provides a list of words that appear in similar contexts to a term throughout the text. Using "similar" for the same term in two texts provides contrast (or comparison) of the how the words are used differently (or similarly) in those texts. 

Similarity information: https://kavita-ganesan.com/what-is-text-similarity/#.Yd8rQd9Omcw

### Word Postions using Dispersion Plots
- Plots where terms appear *throughout a text.*
- Compare multiple terms to see where they appear in the text.

Viewing and comparing where terms appear in a text provids clues to its structure and narrative.

### Word Count

### Lexical Density
- How many unique words per total words aka the ratio  of unique words to total words in a text.
- Useful for understanding complexity of a text. This assumes that unique words = complexity/sophistication of language.

## How to Import Files from Your Computer Into NLTK for Analysis
[NLTK.org](https://www.nltk.org) has an updated copy of Natural Language Processing with Python that provides step-by-step instructions for importing files from your local computer for use with NLTK. See [Chatper 3, "Processing Raw Text"](https://www.nltk.org/book/ch03.html) and scroll to the "Reading Local Files" section.






