## fzf
 - `⌃ + r` search from history
 - `e ** <tab>`
 - `cd ** <tab>`
 - `⌃ + t` trigger fzf 

## pgrep
> find program pid
```
pgrep firefox
```

## lsof
find process on Port 3000
```
lsof -t -i:3000
```
kill it
```
kill -9 $(sudo lsof -t -i:3000)
```

## [thefuck](https://github.com/nvbn/thefuck)
 - Magnificent app which corrects your previous console command.
