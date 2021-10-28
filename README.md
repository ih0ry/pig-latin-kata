## The Pig Latin Kata ##
🚨 This is a test-driven kata, so please write a unit test before each iteration of the code that solves the kata.
We follow the red-green-blue pattern of TDD.

> The challenge is to write a function that converts a word into Pig Latin.

Vowels = a, e, i, o, u

Consonants = [all other letters]

> Examples of a conversion from a normal word to Pig Latin:
- If a word begins with a consonant, it is moved to the back of the word with an added 'ay'. Example:
  Input: `'dough'` Output: `'oughday'`
- Consonant clusters are similarly moved to the back of the word. Example:
  Input: `'chair'` Output: `'airchay'`
- For words that begin with the letter q, the ensuing u is treated as a consonant:
  Input: `'queen'` Output: `'eenquay'`
- Words that begin with vowel sounds simply have 'ay' added to the end:
  Input: `'ahead'` Output: `'aheaday'`
- ...and words consisting solely of consonants are treated the same way:
  Input: `'rhythm'` Output: `'rhythmay'`


> Again, the goal of this kata is to solve it in a test-driven manner. 🔴🟢🔵
> Finally, feel free to use Google and copy/paste
