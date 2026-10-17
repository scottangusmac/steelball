# Steelball

First-person 5-a-side armoured ball game in the browser, in the spirit of Speedball 2. Three classes (Bruiser, Midfield man, Striker), bots fill empty slots.

Play: https://scottangusmac.github.io/steelball/

Multiplayer: enter the arena and a game code is added to the address bar (`#ABCDE`). Send that full link to friends; they join your match. Connections are browser-to-browser via WebRTC ([PeerJS](https://peerjs.com/) public broker for the handshake); the host's browser runs the match.

Single file: `index.html` (three.js r128 and PeerJS 1.5.4 from CDNs).
