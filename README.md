# BashProfiles

Follow this README to pimp up your Mac Terminal!

## How to use
1. Go to user's home directory by entering `cd /` in your terminal.
2. Open `.bash_profile` with your favourite text editor.
3. Copy desired shell scripts/aliases from tables below into `.bash_profile` in any order and save the file.
4. Run `source .bash_profile` in your terminal (make sure you're still in users home directory).

## Useful Aliases

```sh
  alias c='clear'
  alias ls='ls -GFh'
  alias docs='cd && cd Documents/'
  alias Desktop='cd && cd Desktop/'
  alias ..='cd ..'
  alias .='cd '
  alias chrome='/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome'
  alias finder='open -a Finder ./'
  alias ip='ifconfig | grep "inet " | grep -Fv 127.0.0.1 | awk "{print $2}"'
```

## Cool Profiles

Preview | Script
--- | ---
<img src="https://github.com/Arasiga/BashProfiles/blob/master/images/Screen%20Shot%202017-11-08%20at%2012.14.30%20PM.png" width="350" /> | ```export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\t:\[\033[33;1m\]\W\[\033[m\]\$" ```
