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

