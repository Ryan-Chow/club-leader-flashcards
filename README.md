# Club Leader Flashcards

A single-page flashcard app for memorizing club leaders' names, majors, affiliations, and experiences.

**Live:** https://ryan-chow.github.io/club-leader-flashcards/

## Modes
- **Flashcards** – name → details. Mark "Got it" / "Missed it"; missed cards come back sooner and more often.
- **Reverse** – major, affiliation, and a few experiences → name.
- **Quiz** – pick who had a given experience; score and streak are tracked.
- **Study** – every person's full details on one page, with a filter.

Keyboard: `Space` flip, `←`/`→` navigate, `G`/`M` got/missed, `1`–`5` answer quiz.

Everything lives in `index.html` (no build step, works offline). Progress is saved in `localStorage`.
