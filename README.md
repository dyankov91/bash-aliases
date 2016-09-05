# Bash Aliases 
Categories easy to use bash aliases

# Usage

* Download the package and place it inside `~/.bash` folder in your home.

```bash
$ git clone https://github.com/dyankov91/bash-aliases.git ~/.bash
```

* Link it inside your .bashrc (.bash_profile) file.

```bash
# Load generic aliases and functions from a Gist
# -------------------------------------------------------------------------------------
if [ -f ~/.bash/aliases ]; then
    . ~/.bash/aliases
fi
```

* To add your aliases create new file `.bash\user-aliases` and write your aliases there. This file  is going to be loaded by default, but ignored from git.
