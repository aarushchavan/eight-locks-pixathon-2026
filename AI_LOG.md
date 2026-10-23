# AI_LOG.md

## Tools

- Claude: initial game structure and story framework.
- Replit: visual UI improvements and the merged single-file build.
- Codex: puzzle logic review, browser testing, documentation, and GitHub delivery.

## Key prompts and outcomes

These are concise summaries of our requests; they are not claimed as exact transcripts unless quoted.

1. Build a browser-based 2D pixel detective game in which the password is the puzzle. → Initial game structure.
2. Include eight distinct townsfolk the player can question for clues. → NPC roles and conversation UI.
3. Generate a new password for each case with easy, medium, and hard modes. → Case generation and difficulty rules.
4. Add WASD movement, Enter interaction, sound, a journal, and a definite ending. → Play loop and controls.
5. Match the provided cozy pixel village visual reference. → Map and UI direction.
6. Improve the UI while retaining the original password investigation. → Replit's merged visual build.
7. Review the final merged file, remove API dependencies, and prepare a standalone submission. → Final offline-capable build and documentation.

## When AI got it wrong

An intermediate version introduced a Groq service and an optional live NPC API path, which would have required a key and a server. For the final browser-only submission, we removed that path and kept the local, character-specific dialogue and clue rules. We also checked that the final file still generates cases, has all eight NPCs, and ends in success or failure.

## Human direction and verification

The team chose the password-puzzle premise, detective story, pixel-map reference, final merged build, and requirement for a standalone browser game. Codex reviewed the final code and tested the puzzle and interaction flow. AI-generated work was revised to fit those decisions.

## 30-second AI-use pitch

“We used Claude to get the first structure, Replit to refine the pixel UI, and Codex to review the password logic and test the playable browser build. An earlier AI iteration added an API dependency we did not want, so we removed it. The final game runs from one HTML file: every new case has a generated password, eight clue-bearing characters, three difficulties, and a clear ending.”
