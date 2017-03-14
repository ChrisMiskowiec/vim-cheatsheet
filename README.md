# vim-cheatsheet

## Diff

### Open from cmd line

```
> vim -d <file1> <file2>
```

### Navigation

* `ctrl-w, ctrl-w` - Cycle to next window.
* `ctrl-w, n` - Jump to window *n*.
* `]c` - Jump to next change.
* `[c` - Jump to previous change.

### Editing

* `do` - Get changes from other window.
* `[n]do` - Get changes from window *n*.
* `dp` - Put changes into other window.
* `[n]dp` - Put changes into window *n*.

### Misc

* `:diffupdate` - Refresh the diff comparisons.
* `:diffoff` - Turn off diff mode.
