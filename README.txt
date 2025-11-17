# Real-Time Bingo Game with Persistent Boards

## Features
- Teacher calls words from teacher.html
- Players enter their name/ID in player.html
- If board exists in Firebase, it loads; otherwise, a new board is generated and saved
- Boards persist even after refresh

## Setup Steps
1. Host files on GitHub Pages or any web server.
2. Ensure Firebase Realtime Database rules allow read/write for testing:
   {
     "rules": {
       ".read": true,
       ".write": true
     }
   }
3. Share player.html link with students and teacher.html link for caller.
