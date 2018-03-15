# Blue Mood for Gvim and terminal vim

This is a port of [emacs's Blue Mood theme](https://emacsthemes.com/themes/blue-mood-theme.html) for both Gvim and terminal vim. Keep in mind that this port doesn't correspond 100% to the original emacs theme, due to the differences between vim's theming system and emacs's theming system.

## Compatibility notice

This colorscheme is more geared towards the gui, which means that terminal vim is supported only for vim versions 7.4.1799 and up, as from this version onwards, the option `set termguicolors` has been added, which allows for support of gui colors in terminals that have true color support. For more information on this topic, consult [this helpful section](https://github.com/mhinz/vim-galore#true-colors).

## Installation

### Manual

Place the theme file (blue-mood.vim) inside `~/.vim/colors` (Unix) or `vimfiles/colors` (Windows), creating the folder if it doesn't already exist.

### Package managers

```vim
" vim-plug
Plug 'lmintmate/blue-mood-vim'
" NeoBundle
NeoBundle 'lmintmate/blue-mood-vim'
" Vundle
Plugin 'lmintmate/blue-mood-vim'
```
These instructions aren't tested, as I personally use the manual install, but should work.

## Activation

If you are on the gui, just set your colorscheme to blue-mood and you're good to go. If you are on the terminal, and provided that your version of vim is 7.4.1799 and above, first make sure your terminal emulator has true color support ([this gist](https://gist.github.com/XVilka/8346728) might be of help), and then put `set termguicolors` in your vimrc. Afterwards enable the colorscheme as normal.

### Credits

The initial structure for this file was largely based upon [ThemeCreator](https://github.com/mswift42/themecreator). I also consulted several articles of Vim documentation, most prominently the helpscreens `:he group-name`, `:he highlight-groups`, `:he cterm-colors` and the `:highlight` command, and also used [the checklist here](http://vimcasts.org/episodes/creating-colorschemes-for-vim/) to make sure I had styled all important elements.
