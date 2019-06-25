# BashProfiles

Follow this README to pimp up your Mac Terminal!

## How to use
1. Go to user's home directory by entering `cd /` in your terminal.
2. Open `.bash_profile` with your favourite text editor.
3. Copy desired shell scripts/aliases from tables below into `.bash_profile` in any order and save the file.
4. Run `source .bash_profile` in your terminal (make sure you're still in users home directory).

## Useful Aliases

```sh
  alias c='clear' # Clears terminal
  alias ls='ls -GFh' # Shows all files in pwd
  alias docs='cd && cd Documents/' # Redirects you to your documents
  alias desktop='cd && cd Desktop/' # Redirects you to your desktop
  alias ..='cd ..' # Shorthand for going up one directory
  alias .='cd ' # Shorthand for going to root directory
  alias ...='cd ../../' # Go back 2 directory levels
  alias .3='cd ../../../' # Go back 3 directory levels
  alias .4='cd ../../../../' # Go back 4 directory levels
  alias .5='cd ../../../../../' # Go back 5 directory levels
  alias .6='cd ../../../../../../' # Go back 6 directory levels
  alias chrome='/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome' # Opens chrome (Assuming you have it - which you should)
  alias finder='open -a Finder ./' # Opens finder
  alias ip='ifconfig | grep "inet " | grep -Fv 127.0.0.1 | awk "{print $2}"' # Tells you your IP!
```

## Cool Profiles

Preview | Script
--- | ---
<img src="https://github.com/Arasiga/BashProfiles/blob/master/images/Screen%20Shot%202017-11-08%20at%2012.14.30%20PM.png" width="350" /> | ```export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\t:\[\033[33;1m\]\W\[\033[m\]\$" ```
<img src="https://github.com/Arasiga/BashProfiles/blob/master/images/Screen%20Shot%202017-12-31%20at%205.38.37%20PM.png" width="80" /> | ```export PS1="\| => " ```
