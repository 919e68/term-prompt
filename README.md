# Term Prompt

## Requirements

- lolcat
  - rust port (blazingly fast 😅) <https://github.com/ur0/lolcat>

## Clone

```text
git clone https://github.com/919e68/term-prompt.git
cd term-prompt
./install.sh
```

## Config

```text
# add this to the top of .zshrc or equivalent
cat ~/.config/term-prompt/arts/$(ls ~/.config/term-prompt/arts | shuf -n 1) | lolcat
```
