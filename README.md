Bastardized to make the app build


- Because: dependency hell
- Removed: chewie_audio, depended on screen, screen wasn't androidX compat
- Removed: webview, depended on flutter pre 1.20.

We don't use audio or iframes so they can die