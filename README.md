# zsh-customization
Cusotmization of my ZSH environment

## .zshrc

Add the following lines to `.zshrc`

```
# Set up the prompt

fpath=(~/.zsh_custom $fpath)
autoload -Uz promptinit
promptinit
prompt imacube

setopt histignorealldups sharehistory
```

