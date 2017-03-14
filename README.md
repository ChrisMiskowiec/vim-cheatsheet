# vim-cheatsheet

## Buffers

## Windows

### Window Navigation

* `ctrl-w, ctrl-w` - Cycle to next window.
* `ctrl-w, n` - Jump to window *n*.
* `ctrl-w, l` - Jump to window on right.
* `ctrl-w, h` - Jump to window on left.

## Diff

### Open from cmd line

```
> vim -d <file1> <file2>
```

### Navigation

* Use [window navigation](#window-navigation).
* `]c` - Jump to next change.
* `[c` - Jump to previous change.

### Editing

* `do` - Get changes from other window.
* `ndo` - Get changes from window *n*.
* `dp` - Put changes into other window.
* `ndp` - Put changes into window *n*.

### Misc

* `zo` - Open folded lines.
* `zc` - Close folded lines.
* `:diffupdate` - Refresh the diff comparisons.
* `:diffoff` - Turn off diff mode.
