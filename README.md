# fmtmd

A formatter for markdown that doesn't wrap code blocks.

## Usage

Make executable and add to path. Then in `.vimrc` or similar:

```
autocmd FileType markdown setlocal formatprg=fmtmd textwidth=80
```

## Requirements

Python3

## Todo

Make it respect any textwidth instead of just 80.
