# FreeWatch Web

Your PC in a browser: <https://freewatch-brinjal.vercel.app/> (backup: <https://adithya-sd.github.io/freewatch-web/>). The PC can copy a link that carries its pairing code, so opening it pairs at once

- **Pair with a code** once; the browser is remembered after.
- **Sign in with just a password: set it in FreeWatch on the PC (Advanced settings), then type it here. It finds your PC and proves it is you; use a long phrase.
- The picture travels straight between your PC and the browser (WebRTC, encrypted). This page is a static file; nothing runs on a server.
- The password never leaves the page. Both ends turn it into a key with PBKDF2 (600,000 rounds); the key answers a fresh challenge each time, and a name made from it is how the PC is found, so the password alone is enough. The PC makes you wait after wrong tries. Use a long phrase: a short word with a number can be guessed offline.
- Options (link, TURN relay, scaling, scroll, reconnect) are under *Connection options* and the gear.
- Needs a recent Chrome, Edge or Safari (WebCodecs) and the FreeWatch host on the PC.
