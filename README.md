# FreeWatch Web

Your PC in a browser. Open the page, type the pairing code FreeWatch shows on your PC once, and it reconnects on its own afterwards.

- The picture travels straight between your PC and the browser (WebRTC, encrypted). The page is just a static file; nothing runs on a server.
- Each browser holds its own secret key per PC in local storage. Clearing site data forgets them. Forget a browser from the PC's paired-devices list.
- Needs a recent Chrome, Edge or Safari (WebCodecs) and the FreeWatch host on the PC.
