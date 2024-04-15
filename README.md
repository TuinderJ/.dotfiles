# dotfiles for TuinderJ
These dotfiles are setup using stow.

## How to use
Make sure you have stow downloaded.
```
sudo apt install stow
```

CD into your home directory and clone this repository.
```
cd ~
git clone https://github.com/TuinderJ/.dotfiles.git
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

CD into the dotfiles directory that you just cloned and run the stow command.
```
cd .dotfiles
stow --adopt .
```

Load into TMUX and install the plugins.
```
<leader> I
```
