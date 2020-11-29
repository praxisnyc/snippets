# Converting

This is a note for internal use, disregard.

Convert from sublime to atom:
```
cd ~/.atom/snippets/p5js-snippets
atomizr "sublime/*.sublime-snippet" -o atom
```
then consolidate.

Convert from atom to sublime:

```
cd ~/.atom/snippets/p5js-snippets
atomizr "atom/*.cson" -o sublime2
```
pending: review
