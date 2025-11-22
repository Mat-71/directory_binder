# Installation

The recommanded steps for installation are:
- Download `directory_binder` and move it to `~/.local/bin/`;
- Add the following to your rc file:
```sh
if [ -f ~/.local/bin/directory_binder ]; then
    . ~/.local/bin/directory_binder
fi
```
- Optional: make yourself some useful aliases:
```sh
alias db='directory_binder'
alias dba='db add'
alias dbd='db delete'
alias dbl='db list'
alias dbr='db restore'
```

# TODO

## Global options

Make global options usable after the COMMAND.
For example, `directory_binder add -q NAME` should behave the same as
`directory_binder -q add NAME`

## Support enhanced outputs

Add support for colors/bold/etc. in the ouputs, if supported.

## Completion

Add completion, if supported
