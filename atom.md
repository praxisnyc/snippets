

## Atom Install

For atom you need to consolidate snippets after each edit.

1. Move to snippets folder
	- **mac:** `cd /.atom/`
	- **linux:** `pending`
	- **windows:** `pending`
2. create snippets folder: `mkd snippets`
3. clone repository `git clone https://github.com/praxisnyc/code-snippets.git code-snippets`
4. consolidate (below)

## Atom consolidate


1. Install [modular-snippets](https://atom.io/packages/modular-snippets)
2. hit `command-shift-P` and choose `Modular Snippets: Reload`

> Warning: consolidation *replaces* your existing snippets. If you have snippets already, save a copy of `snippets.cson` on `cd /.atom/snippets/` directory

## Atom Update

1. Move to code-snippets folder
	- **mac:** `cd /.atom/snippets/code-snippets`
	- **linux:** `pending`
	- **windows:** `pending`
3. `git pull`
4. consolidate (above)



Huge thanks to [node-atomizr](https://www.npmjs.com/package/node-atomizr) for conversion

# Converting

This is a note for internal use, disregard.

Convert from sublime to atom:
```
cd ~/.atom/snippets/code-snippets
atomizr "sublime/*.sublime-snippet" -o atom
```
then consolidate.

Convert from atom to sublime:

```
cd ~/.atom/snippets/code-snippets
atomizr "atom/*.cson" -o sublime2
```
pending: review

