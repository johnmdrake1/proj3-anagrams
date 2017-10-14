# proj3-anagrams

README:

Author Name: John Drake
Project Repo url: https://github.com/johnmdrake1/proj3-anagrams 
My github page: https://github.com/johnmdrake1/

Description: This webpage, a game, requires a user to enter a word made out of only the scrambled letters shown(i.e. an anagram).
The input also has to match one of the words on a list shown above the entry box. Using a server and python code to communicate
with the client side utilizing HTML and JavaScript, entries are processed by the server to check their validity given
the rules of the game. Each correct word entered prints that word below the text box. When a set number of correct words is
reached(currently 4), the client browser will redirect to a success page with a link to go back to the game.

The initial implementation of the game used a "submit" button when users were ready to send their word to the server.
In this updated and improved version, however, AJAX  interaction is utilized to record and analyze each keystroke along with the
current contents of the text box. When these keystrokes and contents match up with a correct word, the text box is emptied and 
the word is printed below as previously described. This way, no submit button needs to be used or anything such as an "enter"
key pressed.

DEPENDENCIES:
Python 3
Bash
git

INSTRUCTIONS FOR USE:
1. git clone https://github.com/johnmdrake1/proj3-anagrams.git
2. put credentials.ini file in vocab directory(within main project directory)
3. cd proj3-anagrams
4. make install
5. make start
6. Open browser/client and go to localhost:8000
7. Enter 4 correct words in text box. No "enter button" needed
8. Once 4 correct words have been entered, page redirects to success screen
9. Link on success screen can be clicked to play again
10. make stop to stop server 
11. kill | grep python

