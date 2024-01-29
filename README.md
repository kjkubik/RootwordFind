# RootwordFind
Root words, prefixes and suffixes are an important part of the English language. I was unable to find a way to search the Bible for these. 
So here is my attempt at searching for words only have a root word, prefix or suffix.

INPUT: https://bible.knowing-jesus.com/words - copied all words in the bible (webscrapping could be completed...I didn't find it worth my time for this, though.)

PREFIX: Just find words beginning with prefix...pretty simple
SUFFIX FIND: INPUTWORDS -> reverse order of each word -> sort words -> select words beginning with reverse of suffix -> reverse order of each reverse word containing suffix -> list of words with suffix
ROOT WORD: Search each word for the root

This is trickier than it looks because you don't know the length of the word; and, it might be quicker to just reverse and sort as I have. I don't know. I was doing this to practice manipulating data, more than anything.


