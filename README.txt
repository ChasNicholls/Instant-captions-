Instant Captioner
====================
A minimal PWA that uses your device microphone to show real-time captions (e.g., for TV audio).

Quick start
-----------
1) Unzip these files and open index.html in Chrome/Edge (desktop) or Android Chrome. For iOS, use Safari.
2) Click **Start**, allow microphone access, and point the device mic toward your TV.
3) Use the **Font** slider and **Fullscreen** for readability. Save transcripts with **Save .txt**.

Install to Home Screen (PWA)
----------------------------
Serve over HTTPS (or open as a local file for testing). If you host on GitHub Pages, it will be HTTPS by default.
A basic service worker is included for offline capability (the recognition still needs network per browser vendor).

Tips for better accuracy
------------------------
• Move the device closer to the TV speaker. Reduce room noise.
• Try **en-AU** for Aussie TV. Pick language in the selector.
• Toggle **show interim** for faster (but sometimes messy) live text.
• Some browsers end sessions after a while—"auto-restart" tries to keep it alive.

Known limitations
-----------------
• Web Speech API availability varies by browser and OS, and vendors may route audio to their cloud for STT.
• Selecting a specific microphone from inside the page is limited; use system/browser settings to choose input.
• Background noise, echo, and music can reduce accuracy.
• iOS Safari requires user gesture to start; keep the page in the foreground.

Keyboard shortcuts
------------------
S = start/stop, C = clear, F = fullscreen, Ctrl/⌘+S = save transcript.

Built 2025-09-08T04:30:15.621136Z
