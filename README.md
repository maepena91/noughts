# Noughts
I created game known as Noughts and Crosses. I ran into the name when I was looking at a coding book for kids. I was inspired to make this game because I used to play this game growing up using a paper and pencil with my classmates or the neighborhood friends. Now I have the opportunity to create it through a web browser!
The way I started creating the game is by starting with my HTML file. I added a header that includes the name of the game. Then I added a section tag with the class of container. This will help with the styling and adjusting portion. Then I added nine total divs which will be part of our tic tac toe table. I gave each one a class and an Id. Class was for the styling and the id will be for the javaScript interaction. When the game is over, instead of refreshing the page to start the game over, I added a reset button which will clear the X's and O's for both players to play a game. 
On the bottom of the divs, you will see the button tag, and the script tag. 
In the JavaScript portion, you will see that it starts with adding querySelectors for each div/square. This will target each div/square with the help of the Id's. There is also a list of an array and it contains a combination of different ways to win. Switch statements were added for each square with a plus winner to help with the increment number of X's and O's. If and else statements are in control of the winner and the announcement of the winner. The event listeners are responsible for the click of each square. Once the player clicks on one square, the letter wont change and the next person is next. 
references:
https://pixabay.com/images/search/pencil/
pencil-g0ee375857_1280.jpg
