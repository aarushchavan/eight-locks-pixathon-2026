# Eight Locks: The Midnight Cipher

A single-file browser detective game for the Pixathon password puzzle challenge. Open `index.html` in a modern browser to play. No installation, server, API key, or account is required.

## Story and play

Archivist Elias Vance vanished after finding evidence that Saltmere's harbour fund was being drained. His ledger is sealed in the clocktower behind a password. As Detective Rook, question eight townsfolk, collect their rules in your journal, and solve the password before the final bell.

Each new case chooses a fresh password from a curated word pool and derives eight consistent clues from it. Easy, medium, and hard change the number of days, guesses, clue directness, and danger. NPCs respond to typed questions using local, character-specific dialogue rules. Their replies and clue delivery run entirely in the browser; there is no live language model or network API. The game has success and failure endings and can generate another case afterward.

## Controls

WASD or arrow keys to move; Enter or E to interact; Shift to dash; Q for detective sense; N for the journal. Type questions in the dialogue box and enter a guess at the clocktower vault. Sound can be toggled in the HUD. Browser audio starts after a user interaction.

## Technical notes

The world, pixel art, interface, puzzle generation, dialogue, and synthesized sounds are contained in `index.html`. Google Fonts are optional; the game falls back to local fonts when offline. No key or private configuration is part of this submission.

## AI use

Claude helped generate the first game structure. Replit helped improve the visual UI. Codex worked on puzzle logic, integration, local testing, documentation, and GitHub preparation. AI was used to build the game, not to serve live NPC replies in this final version. See [AI_LOG.md](AI_LOG.md) for the key prompts, correction, and team decisions.
