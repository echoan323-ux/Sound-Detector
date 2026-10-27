# Sound Detective
Responsive educational app using HTML, CSS, and vanilla JavaScript.

## Run
From this folder, run `python3 -m http.server 8000` and open `http://localhost:8000`. A server is necessary because the app fetches `lessons.json`. For microphone access on a deployed site, use HTTPS (localhost also works).

## Customize
Edit `lessons.json`. Each lesson has `id`, `title`, `sounds`, `tip`, and `pairs` (arrays of two words). Keep IDs unique. Audio uses browser SpeechSynthesis (en-US); available voices and fidelity vary by device. Listening quiz chooses one word from each pair twice in randomized order. Progress (completion and best quiz score) uses localStorage. Voice recordings remain in memory for playback and are not uploaded or stored in localStorage. No AI scoring or backend.


## Expanded lessons
This edition includes 20 sound-pair lessons in `lessons.json`. Keep each `id` unique. The homepage lesson count updates automatically.
