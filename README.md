# Hangman

## Due: Mon 11/14 at 11:59 PM

- Create a program called `Hangman.java`
- Prompt the user for a word
  - This will be the word the player tries to guess
- Print several blank lines to clear the screen
- Print the hidden word
  - Replace the letters with dashes
- Prompt the user for a letter until the user has guessed all the letters in the word or has made 9 incorrect guesses
- Output whether the guess is correct or not
- Print the hidden word with any correct guesses revealed and the number of incorrect guesses left
- Once the game is over, output whether the user is a winner or a loser
  - If the user is a winner, print how many total guesses it took
  - If the user is a loser, print the correct word

***Example Input:***\
elephant\
r\
s\
t\
l\
n\
e\
p\
h\
a\
***Example Output:***\
--------, 9 incorrect guesses left\
Enter a letter: \
r is not in the word\
--------, 8 incorrect guesses left\
Enter a letter: \
s is not in the word\
--------, 7 incorrect guesses left\
Enter a letter: \
t is in the word\
-------t, 7 incorrect guesses left\
Enter a letter: \
l is in the word\
-l-----t, 7 incorrect guesses left\
Enter a letter: \
n is in the word\
-l----nt, 7 incorrect guesses left\
Enter a letter: \
e is in the word\
ele---nt, 7 incorrect guesses left\
Enter a letter: \
p is in the word\
elep--nt, 7 incorrect guesses left\
Enter a letter: \
h is in the word\
eleph-nt, 7 incorrect guesses left\
Enter a letter: \
a is in the word\
Congratulations! You guessed elephant in 9 guesses!

***Example Input:***\
bobcat\
r\
s\
t\
l\
n\
e\
a\
i\
o\
d\
f\
h\
***Example Output:***\
------, 9 incorrect guesses left\
Enter a letter: \
r is not in the word\
------, 8 incorrect guesses left\
Enter a letter: \
s is not in the word\
------, 7 incorrect guesses left\
Enter a letter: \
t is in the word\
-----t, 7 incorrect guesses left\
Enter a letter: \
l is not in the word\
-----t, 6 incorrect guesses left\
Enter a letter: \
n is not in the word\
-----t, 5 incorrect guesses left\
Enter a letter: \
e is not in the word\
-----t, 4 incorrect guesses left\
Enter a letter: \
a is in the word\
----at, 4 incorrect guesses left\
Enter a letter: \
i is not in the word\
----at, 3 incorrect guesses left\
Enter a letter: \
o is in the word\
-o--at, 3 incorrect guesses left\
Enter a letter: \
d is not in the word\
-o--at, 2 incorrect guesses left\
Enter a letter: \
f is not in the word\
-o--at, 1 incorrect guess left\
Enter a letter: \
h is not in the word\
You lost! The word was bobcat
