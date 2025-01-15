# ddc-source-shell-history

Shell history completion for ddc.vim

This source collects items from shell history file.

## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddc.vim

https://github.com/Shougo/ddc.vim

## Configuration

```vim
call ddc#custom#patch_global('sources', ['shell-history'])

call ddc#custom#patch_global('sourceOptions', {
      \   "shell-history": #{
      \     mark: 'history',
      \   }
      \ })

call ddc#custom#patch_global('sourceParams', {
      \   "shell-history": #{
      \     paths: ['~/.zsh-history'],
      \   }
      \ })
```
