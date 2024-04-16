# dotfiles for TuinderJ
These dotfiles are setup using stow.

## How to use
Make sure you have stow downloaded.
CD into your home directory and clone this repository.
Also clone the TPM repository.
CD into the dotfiles directory that you just cloned and run the stow command.
``` debian
cd ~ &&\
sudo apt install stow &&\
git clone git@github.com:TuinderJ/.dotfiles.git && \
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm &&\
cd .dotfiles &&\
stow --adopt .
```

``` arch 
cd ~ &&\
sudo pacman -S stow &&\
git clone git@github.com:TuinderJ/.dotfiles.git && \
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm &&\
cd .dotfiles &&\
stow --adopt .
```

Load into TMUX and install the plugins.
```
<leader> I
```
