# code-snippets

<a href="https://praxis.nyc"><img src="https://praxis.nyc/assets/favicons/apple-touch-icon.png" width="60px" height="60px" /></a>

Snippets for your creations. For Sublime and Atom.

> Questions? Comments? Debugging? [Join our group on keybase](https://keybase.io/team/praxis_nyc).

|Snippets|||
|---|---|---|
|[CSS](https://github.com/praxisnyc/code-snippets/tree/master/CSS#requirements)|[html](https://github.com/praxisnyc/code-snippets/tree/master/html#requirements)|[SASS](https://github.com/praxisnyc/code-snippets/tree/master/SASS#requirements)|
|[bootstrap](https://github.com/praxisnyc/code-snippets/tree/master/bootstrap#requirements)|[CDN](https://github.com/praxisnyc/code-snippets/tree/master/CDN#requirements)|[animation](https://github.com/praxisnyc/code-snippets/tree/master/animation#requirements)|
|[family](https://github.com/praxisnyc/code-snippets/tree/master/family#requirements)|[gulp](https://github.com/praxisnyc/code-snippets/tree/master/gulp#requirements)|[markdown](https://github.com/praxisnyc/code-snippets/tree/master/markdown#requirements)|
|[snippets](https://github.com/praxisnyc/code-snippets/tree/master/snippets#requirements)|[nunjucks](https://github.com/praxisnyc/code-snippets/tree/master/nunjucks#requirements)|[social](https://github.com/praxisnyc/code-snippets/tree/master/social#requirements)|
|[wordpress](https://github.com/praxisnyc/code-snippets/tree/master/wordpress#requirements)|[regex](https://github.com/praxisnyc/code-snippets/tree/master/regex#requirements)|[sublime](https://github.com/praxisnyc/code-snippets/tree/master/sublime#requirements)|
|[p5js](https://github.com/praxisnyc/code-snippets/tree/master/p5js#requirements)|


## Sublime Text Install

1. Move to snippets folder (change to `2` if previous version)
	- **mac:** `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages`
	- **linux:** `cd ~/.config/sublime-text-3/Packages`
	- **windows:** `cd "%AppData%\Sublime Text 3\Packages\User"`
2. clone repository `git clone https://github.com/praxisnyc/code-snippets.git code-snippets`


## Sublime Text Update

1. Move to code-snippets folder (change to `2` if previous version)
	- **mac:** `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/code-snippets`
	- **linux:** `cd ~/.config/sublime-text-3/Packages/code-snippets`
	- **windows:** `cd "%AppData%\Sublime Text 3\Packages\User\code-snippets"`
2. `git pull`

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

### Troubleshooting

`SASS` and `SCSS` snippets can't be triggered on `css` files. If you DON’T have `Sass` listed, install `Sass` (Sass support for TextMate and Sublime Text) package.

If trigger is still not working, open `preferences > settings` and add `"auto_complete_selector": true`

Huge thanks to [node-atomizr](https://www.npmjs.com/package/node-atomizr) for conversion
