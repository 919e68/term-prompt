# Terminal Greeter

## Requirements

- lolcat

## Clone

```text
$ git clone
```

## Config

```text
# add this to the top of .zshrc or equivalent
cat ~/ascii-art/arts/$(ls ~/ascii-art/arts | shuf -n 1) | lolcat
```
