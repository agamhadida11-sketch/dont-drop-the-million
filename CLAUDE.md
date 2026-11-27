# אל תפיל את המיליון (Don't Drop the Million)

A two-player Hebrew TV-studio quiz game, built as a single page: `index.html`.

## About the user
- The user writes in Hebrew and is not technical. Answer in simple Hebrew, step by step, and do the technical work yourself.
- They often work from their phone. Don't ask them to run commands or use desktop tools.

## The game
- Everything (HTML, CSS, JS, WebGL stage) lives in `index.html`. The UI is right-to-left Hebrew.
- It is published as a claude.ai Artifact: https://claude.ai/artifact/RYnXADVLkyrgrtZHdbZT4j
- It relies on the Artifact runtime capabilities `db`, `room` and `user` (two devices share one room code), so multiplayer only works when served as that Artifact, not from a plain file or GitHub Pages.

## Workflow
- After a change: commit with a short message and push to `main` (this repo is private on GitHub).
- If the Artifact tool is available, also republish `index.html` to the Artifact URL above so the playable link updates.
