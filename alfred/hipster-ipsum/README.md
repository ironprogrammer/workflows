# Hipster Ipsum

An Alfred workflow that generates hipster-ipsum placeholder text and drops it into the frontmost app (and onto the clipboard). Handy filler for mockups, design comps, and local dev.

## Install

**[Download Hipster-Ipsum.alfredworkflow](../../alfred/Hipster-Ipsum.alfredworkflow?raw=true)** — double-click to install in Alfred.

## Usage

Type `hipster` followed by any of these — all optional, in any order:

- **count** — a number 1–99 (how many paragraphs or sentences)
- **format** — `paras`/`p` or `sentences`/`s`
- **type** — `centric` (default) or `latin`
- **baby** — start the text with "I'm baby..."

Examples:

- `hipster` → 1 paragraph
- `hipster 3` → 3 paragraphs
- `hipster 5 sentences` → 5 sentences
- `hipster 2 latin` → 2 latin paragraphs
- `hipster baby` → starts with "I'm baby..."

The result is pasted into the frontmost app and left on the clipboard.

## Credits

Based on [tofias' workflow gist](https://gist.github.com/tofias/9160634), itself based on [Seth Lilly's Hipster-Ipsum-for-Coda](https://github.com/sethlilly/Hipster-Ipsum-for-Coda). Placeholder text comes from the [Hipster Ipsum API](https://hipsum.co) by Jason Cosper.
