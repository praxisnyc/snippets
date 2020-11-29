# snippets


Sublime snippets for quick coding (and less syntax errors).


|Snippets|||
|---|---|---|
|[CSS](https://github.com/nonlinear/snippets/blob/main/CSS#requirements)|[html](https://github.com/nonlinear/snippets/blob/main/html#requirements)|[SASS](https://github.com/nonlinear/snippets/blob/main/SASS#requirements)|
|[bootstrap](https://github.com/nonlinear/snippets/blob/main/bootstrap#requirements)|[CDN](https://github.com/nonlinear/snippets/blob/main/CDN#requirements)|[animation](https://github.com/nonlinear/snippets/blob/main/animation#requirements)|
|[family](https://github.com/nonlinear/snippets/blob/main/family#requirements)|[gulp](https://github.com/nonlinear/snippets/blob/main/gulp#requirements)|[markdown](https://github.com/nonlinear/snippets/blob/main/markdown#requirements)|
|[snippets](https://github.com/nonlinear/snippets/blob/main/snippets#requirements)|[nunjucks](https://github.com/nonlinear/snippets/blob/main/nunjucks#requirements)|[social](https://github.com/nonlinear/snippets/blob/main/social#requirements)|
|[wordpress](https://github.com/nonlinear/snippets/blob/main/wordpress#requirements)|[regex](https://github.com/nonlinear/snippets/blob/main/regex#requirements)|[sublime](https://github.com/nonlinear/snippets/blob/main/sublime#requirements)|
|[p5js](https://github.com/nonlinear/snippets/blob/main/p5js#requirements)|


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

### Troubleshooting

`SASS` and `SCSS` snippets can't be triggered on `css` files. If you DON’T have `Sass` listed, install `Sass` (Sass support for TextMate and Sublime Text) package.

If trigger is still not working, open `preferences > settings` and add `"auto_complete_selector": true`