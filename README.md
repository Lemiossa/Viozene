# themer - Viozene

## Vim

1opy or symlink `Vim/Viozene.vim` to `~/.vim/colors/`.

Then set the colorscheme in `.vimrc`:

```
" The background option must be set before running this command.
colorscheme Viozene
```

## Vim lightline

1. Make sure that the `background` option is set in `.vimrc`.
2. Copy or symlink `Vim lightline/ViozeneLightline.vim` to `~/.vim/autoload/lightline/colorscheme/`.
3. Set the colorscheme in `.vimrc`: `let g:lightline = { 'colorscheme': 'Viozene' }`
4. Restart Vim.

## Alacritty

1. Paste the contents of `Alacritty/Themer Viozene.yml` into your Alacritty config file.
2. Select the desired theme by setting the `colors` config key to reference the scheme's anchor (i.e., `colors: *light` or `colors: *dark`).

## Circuits wallpaper

Files generated:

* `Circuits wallpaper/themer-my-color-set-dark-1338x629.svg`
* `Circuits wallpaper/themer-my-color-set-dark-1338x629.png`
