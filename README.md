# spell-check
This is a program that does what Microsoft Word does with spell check. If a word is not found in the dictionary it has loaded, it compares the dictionary with a loaded novel to find the relative frequency of word usage. It then suggests the three words that are the closest in spelling and are most commonly used. 
It uses a somewhat-complicated algorithm where it sorts words into how close they are in spelling (one change away, two changes away, etc, where a change can be a transposition, an alteration (where the wrong letter was typed), addition (where an extra letter was typed) or a subtraction (where a letter was not typed that should have been)). It then finds the most frequently used words that have the least number of changes and displays those.