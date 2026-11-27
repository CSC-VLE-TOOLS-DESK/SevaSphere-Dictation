# SevaSphere Dictation
Speak and it types. Hindi, English and 15+ languages. Static site, no build step.

## Run
Push these files to the repo root, then Settings > Pages > Deploy from branch (main, /root).
Local test: `python3 -m http.server 8000` and open http://localhost:8000 in Chrome or Edge.

## Link the family
In index.html edit the `FAMILY` list (SevaSphere, Kids Corner) and add the Dictation link on those sites.

## Notes
- Speech recognition is done by the browser vendor (Chrome/Edge send audio to their service).
- Translate uses the free MyMemory API; text you translate is sent to that service.
- Installable on phone and desktop (PWA). Dictation needs internet; notes and editing work offline.

## Layout (v4)
- One full-window screen that fits any size or browser zoom (no page scrolling on desktop).
- Header: language and options. Toolbar below it: all action buttons (wraps to extra rows only when the window is narrow).
- Left sidebar: Voice commands, Snippets, Notes. Right sidebar: Voice studio and Recordings.
- On phones (under 820 px wide) the sidebars slide in from the toolbar buttons.
