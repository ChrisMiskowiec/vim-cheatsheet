# vim-cheatsheet

## Diff

### Open from cmd line

```
> vim -d <file1> <file2>
```

### Navigation

* `ctrl-w, ctrl-w` - Cycle to next window.
* `ctrl-w, n` - Jump to window *n*.
* `ctrl-w, l` - Jump to window on right.
* `ctrl-w, h` - Jump to window on left.
* `]c` - Jump to next change.
* `[c` - Jump to previous change.

### Editing

* `do` - Get changes from other window.
* `ndo` - Get changes from window *n*.
* `dp` - Put changes into other window.
* `ndp` - Put changes into window *n*.

### Misc

* `:diffupdate` - Refresh the diff comparisons.
* `:diffoff` - Turn off diff mode.
