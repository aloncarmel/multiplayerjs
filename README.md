# MultiplayerJS
A Multiplayer JS Library using Firebase to add Figma/Miro like multiplayer experience to any web page in real time

## This library offers a simple js file that you can add to any page
* Using Firebase as the real-time engine to drive the real-time experience (Required to use)
* Multiplayer exeprience based on unique page url the library is loaded on
* Multi-cursor on page for each new user joining the page
* Commenting on page, comment saved based on X,Y where the user has add the comment with simple textbox 
* Added connected users (Random username and color generated) to the bottom right side whenever a user joins page

## Requirements
* Active public firebase account and base url open for anonymous write event
* Firebase SDK loaded on page succesfully
* JQuery loaded on page succesfully

## Required libraries loaded on page
* <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
* <script src="https://www.gstatic.com/firebasejs/7.17.2/firebase-app.js"></script>
* <script src="https://www.gstatic.com/firebasejs/7.17.2/firebase-firestore.js"></script>
* <script src="https://www.gstatic.com/firebasejs/7.17.2/firebase-database.js"></script>
