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
