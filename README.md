# ddc-source-shell_history

Shell history completion for ddc.vim

This source collects items from shell history file.

## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddc.vim

https://github.com/Shougo/ddc.vim

## Configuration

```vim
call ddc#custom#patch_global('sources', ['shell_history'])

call ddc#custom#patch_global('sourceOptions', #{
      \   shell_history: #{
      \     mark: 'history',
      \   }
      \ })

call ddc#custom#patch_global('sourceParams', #{
      \   shell_history: #{
      \     paths: ['~/.zsh-history'],
      \   }
      \ })
```
