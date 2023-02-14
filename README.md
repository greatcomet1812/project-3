# UOCIS322 - Project 3 #

Author: Sewon Sohn\
Contact: ssohn@uoregon.edu\

The program is a simple anagram game designed for English-learning students in elementary and middle school. It presents a list of words to students and an anagram. The anagram is a jumble of some of the words, which are randomly chosen. Students attempt to type words that can be created from the jumble. When a matching word is typed, it is added to a list of solved words.

The vocabulary word list is fixed for one invocation of the server, so multiple students connected to the same server will see the same vocabulary list but may have different anagrams.

An error message is displayed if the word is not in the vocabulary, cannot be made from the anagram, or is already found. 
