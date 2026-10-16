# Fuga Romana — Level 1 Escape Room

A 15-question Latin escape room covering the whole of ISEB Common Entrance Level 1, built on *Prep School Latin* by R. C. Bass (Chapters 2–73).

Open `index.html` in a browser, or serve the folder with GitHub Pages. The page is a single file with no build step.

## How it works

- **Grammar tick-boxes.** Eighteen grammar points in Bass's order, from amo/moneo verbs (Ch 2) to the perfect tense (Ch 60–73). Preset buttons tick everything up to Ch 8, 19, 38, 56 or the whole of Level 1. The page remembers the last selection on that device.
- **Only the ticked grammar.** Every sentence in the bank is tagged with every grammar point it uses. A sentence appears only if all of its tags are ticked. If fewer than 15 sentences fit, the Start button stays off and the page says so.
- **Question types.** Translate (choose the English), unscramble the Latin (with wrong-ending decoys where Bass's forms allow), choose the right form for a gap, and parse a word (person and number, case and number, or tense).
- **Three stories**, one picked at random each game: The Locked School, The Shipwreck, The Siege. Five rooms of three locks each.
- **Grammar table** button on every question shows the relevant Bass table.
- **End screen** shows the score (correct first time), the grammar points to revise with Bass chapter references, and all 15 answers.

## The question bank

All Latin comes from Bass: 463 sentences from the Latin-to-English exercises and the Flavia and the Sailor passages, each checked word-for-word against the book. Gap options and decoys are forms that appear in the book. The English translations and wrong English options were written for this game, as Bass prints no answer key.

The bank sits in the `BANK` section of `index.html`. Each line reads:

```
T(chapter, 'latin', 'English', 'grammar tags', ['wrong 1', 'wrong 2', 'wrong 3'], { u, g, p })
```

Grammar tags A–R are listed in `GRAMMAR` near the top of the script.

## Licence

Latin sentences and grammar tables from *Prep School Latin* (R. C. Bass, 2018), used under a Creative Commons Attribution-NonCommercial-ShareAlike licence. This game is shared under the same licence.
