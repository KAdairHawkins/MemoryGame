# MemoryGame
Not your average memory game

This is a twist on a class memory game. The application is built with ReactJS, Material CSS, and Node.js.

The user enters interest into search bar which creates 12 image cards. The cards are grabbed with AJAX from giphyAPI. To win, the user clicks each image only once, but each time the user clicks an image, the cards shuffle. If the user is successful, the application increases the user's score.

The user's score is reset to 0 if the same image is selected more than once. After this, the application increases the user's loss count and the game restarts.
