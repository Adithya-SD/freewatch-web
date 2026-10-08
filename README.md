# FreeWatch Web

Your PC in a browser: <https://freewatch-brinjal.vercel.app/> (backup: <https://adithya-sd.github.io/freewatch-web/>). The PC can copy a link that carries its pairing code, so opening it pairs at once

- **Pair with a code** once; the browser is remembered after.
- **Sign in with a permanent password** from any browser: in FreeWatch on the PC, open *Advanced settings*, *Copy web link*, open it and type the password. Set the password from a signed-in browser or phone (key button).
- The picture travels straight between your PC and the browser (WebRTC, encrypted). This page is a static file; nothing runs on a server.
- The password never leaves the page: a key derived from it (PBKDF2, 200,000 rounds, salted with the PC id) answers a fresh challenge each time. The PC makes you wait after wrong tries.
- Options (link, TURN relay, scaling, scroll, reconnect) are under *Connection options* and the gear.
- Needs a recent Chrome, Edge or Safari (WebCodecs) and the FreeWatch host on the PC.
