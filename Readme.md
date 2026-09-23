# Babel Gavel: Language Triangle

Web version of the Babel Gavel language structure explorer (Saxion, Quest 3).
It takes the five Dutch rule verification sentences and runs them through a
small rule engine for Dutch, Korean, Turkish, French and Slovak.

## Features
- **Dutch**: JavaScript port of `RuleEngine.java` (rules 1–5), with a rule selector
- **Korean / Turkish / French / Slovak**: word-for-word translation, then
  language-specific rules applied step by step (verb-final, clitic second
  position, negation affixes, elision, …)
- Animated token reordering, interlinear gloss per language
- Contrast table: verb position, fronting, negation, verbs that split
- "Copy for Quest Journal" export

## Run
Open `index.html` in a browser. No build step, no dependencies.

To host with GitHub Pages: Settings → Pages → deploy from branch `main`, folder `/ (root)`.

## Notes
- Word lists cover only the five test sentences, like the original tool.
- Roles Object, Adverb and Particle extend the five Babel Gavel roles.
- Slovak examples use masculine forms.
