# Pig_Latin_Translator
Translates into pig latin; Python

## One Word
The one word version asks the user for one word, and then translates that word into pig latin based on the rules of pig latin. The rules of pig latin are: remove the first letter of the word, place the first letter of the word at the end of the word, and add "ay" to the end of the word. In the first version, the program ends after one word is translated, but in the second version, the user is asked if they would like another word to be translated. They can enter as many words as they want.

## Whole Sentence
In the whole sentence version, the user is asked for a sentence where each word is translated into pig latin. Certain bugs from the one word version are fixed, like if a user enters something other than "yes" or "no" to the question asking if they would like to enter another sentence, it reprompts the question rather than just continuing to ask them for another string. 

## Bugs to still be fixed
If a user enters a space at the end of the sentence, there is a runtime error saying the function defined cannot run because the string index is out of range.

Need to account for if a user puts a piece of punctuation at the end of their sentence. Would like to conserve the punctuation mark they use.

Want to account for capitalization. For example, if they include a proper noun, the translated word should also be capitalized in translation.
