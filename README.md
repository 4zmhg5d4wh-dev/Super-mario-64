# Super Mario 64 — Web App wrapper

This is a small installable web-app shell that loads the original game from:
https://notan127.github.io/SM64-PC-Port-WebGL/

## Important
- This package does not contain or modify the original game.
- It needs an HTTPS host (for example, a GitHub Pages site) before it can be installed.
- The service worker caches only this wrapper shell. The game itself still loads from its original website and may require internet.
- The original game must permit being displayed in an iframe. If it blocks embedding, this wrapper cannot bypass that restriction; the original project would need to be adapted by its maintainers.
- Touch controls, audio, fullscreen, and gamepad behavior depend on the original game and iOS support.

## Files
Upload the contents of this folder to the root of an HTTPS static website.
