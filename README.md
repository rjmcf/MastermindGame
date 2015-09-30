# MastermindGame
So far a text-based Mastermind game, that allows you to try and crack the code created by the computer!

The code is 4 letters long, where the letters can be a,b,c,d,e,f. There are four levels, 
 
  - Level 1: There can be no repeated letters in the code, so "aabc" is not a possible code.
  - Level 2: There may be repeated letters in the code, so "aabc" is now possible.
  - Level 3: There is now a 7th letter possible in the code, g, but no repeats, so while "abcg" is possible, "aacg" is not.
  - Level 4: As well as the 7th letter, there may now be repeated letters, so "aacg" is a possible code.
  
The feedback given in response to your guess is as a number of "r"s and "w"s. The number of "r"s corresponds to how many letters in your guess are both the correct letter and in the correct location. The number of "w"s corresponds to how many letters in your guess are the correct letter, but in the wrong location. A single letter can not be counted with both an "r" and a "w", it is one or the other.

Functionality to create your own code and allowing the computer to attempt to crack it is on the way, but the algorithms are hard!
