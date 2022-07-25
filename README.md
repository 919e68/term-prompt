# Terminal Greeter

## Requirements

- lolcat

## Clone

```text
$ git clone https://github.com/919e68/terminal-greeter.git
$ cd terminal-greeter
$ ./install.sh

```

## Config

```text
# add this to the top of .zshrc or equivalent
cat ~/.config/terminal-greeter/arts/$(ls ~/.config/terminal-greeter/arts | shuf -n 1) | lolcat
```
