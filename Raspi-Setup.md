# Setup Of Raspberry Pi Computers for hidenet

## Additional Software

### Powerline-shell

* Install powerline-shell:
`pip install powerline-shell`

* Configure powerline-shell:
Add the following to your .bashrc file:
```function _update_ps1() {
    PS1=$(powerline-shell $?)
}

if [[ $TERM != linux && ! $PROMPT_COMMAND =~ _update_ps1 ]]; then
    PROMPT_COMMAND="_update_ps1; $PROMPT_COMMAND"
fi
```

## Setup Files



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NTk0MjAwNzEsLTE0NjgxMzAyNDJdfQ
==
-->