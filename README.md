# Blue Mood for Gvim

This is a port of [emacs's Blue Mood theme](https://emacsthemes.com/themes/blue-mood-theme.html) for Gvim.
It is for the moment compatible only with it and not with the terminal version of Vim.
Keep in mind that this port doesn't correspond 100% to the original emacs theme, due to the differences between vim's theming system and emacs's theming system.

## Installation & Activation

Only manual for the moment.
Place the theme file (blue-mood.vim) inside `~/.vim/colors`, creating it if it doesn't already exist.

### Credits

The initial structure for this file was largely based upon [ThemeCreator](https://github.com/mswift42/themecreator). I also consulted several articles of Vim documentation, most prominently the helpscreens `:he group-name`, `:he highlight-groups`, `:he cterm-colors` and the `:highlight` command, and also used [the checklist here](http://vimcasts.org/episodes/creating-colorschemes-for-vim/) to make sure I had styled all important elements.
