Rock Paper Scissors Arena 🎮
A friendly, real-time Rock–Paper–Scissors game for two players on separate devices, powered by Firebase Realtime Database.
Features
Create a room and share its six-character code.
Join from another device using the room code.
Rock, Paper, Scissors choices sync through Firebase.
Moves are revealed when both players have chosen.
Play another round without leaving the room.
Responsive layout for phones and desktops.
Firebase setup
This project uses the Firebase web app configuration for the rock-paper-scissors-aren-1ccea project and the Realtime Database in asia-southeast1.
Important: The frontend is not secure enough for a public production launch yet. Do not use it for private information or real-money play. Before sharing widely, add Firebase Authentication and stricter database rules. The demo requires read/write permissions under /rooms for room synchronization; avoid opening the entire database root.
Run / deploy
Enable the database rules required for the demo (see database.rules.json).
Publish index.html with GitHub Pages or another static host.
Open the published website on two separate devices and test a room.
Files
index.html — complete game, responsive UI and Firebase connection.
database.rules.json — demo rules template; review security before publishing.# rock-paper-scissors-arena