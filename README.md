# dotfiles

```
mkdir ~/code
cd ~/code
git clone git@github.com:bigbinary/bb-dotfiles.git
```

Open `~/.zshrc` file and add the following two lines at the very bottom.

```
source "$HOME/code/bb-dotfiles/aliases"
export PATH="$HOME/code/bb-dotfiles/base/scripts:$PATH"
```
