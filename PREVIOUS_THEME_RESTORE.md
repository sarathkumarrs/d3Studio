# Previous Theme Restore

Use this file when you want the website returned to the earlier dark theme.

## What to do

Restore the previous theme by removing the CSS block labeled:

`/* --- LIGHT THEME REFRESH --- */`

from:

`index.html`

## Why this works

The original dark theme styles are still present earlier in `index.html`.
The current light look was added only as an override block near the end of the `<style>` section.
So reverting does **not** require rebuilding the old CSS manually.

## Result after restore

Removing that override block will bring back:

- the dark overall site theme
- the boxed logo treatment in the header
- the darker navbar, sections, cards, forms, and footer

## Instruction to give later

If you want this reverted in a future prompt, you can simply say:

`Follow the instructions in PREVIOUS_THEME_RESTORE.md`
