# zsh 

## when zsh becomes slow 👿, try this 🥺

### see zsh load detail

```bash
zmodload zsh/zprof # top of your .zshrc file

setopt no_beep
......

zprof # bottom of .zshrc
```

### easy quick zsh loading time benchmark

```bash
for i in $(seq 1 10); do /usr/bin/time zsh -i -c exit; done
```

### `(eval):1: command not found: node`

See this [problem](https://github.com/denysdovhan/spaceship-prompt/issues/524)
`upgrade_oh_my_zsh` to update oh-my-zsh, sometimes fix some problems, 


## terminal tools

### fzf

 - [refenerce](https://github.com/junegunn/fzf)
 - `⌃ + r` search from history
 - `e ** <tab>`
 - `cd ** <tab>`
