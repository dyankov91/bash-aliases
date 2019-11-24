# Shell Aliases 
Categorised easy to use shell aliases

# Usage

* Download the package and place it inside `~/.sh` folder in your home.

```sh
$ git clone https://github.com/dyankov91/bash-aliases.git ~/.sh
```

* Link it inside your .bashrc (.bash_profile) / .zshrc (.zprofile) file.

```sh
# Load generic aliases and functions from a Gist
# -------------------------------------------------------------------------------------
if [ -f ~/.sh/aliases ]; then
    . ~/.sh/aliases
fi
```

* To add your aliases create new file `.sh\user-aliases` and write your aliases there. This file  is going to be loaded by default, but ignored from git.
