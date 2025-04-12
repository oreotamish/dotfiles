Go to ~/.config
mv dotfiles/* .
rm -rf dotfiles

also install tmp 
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
starship is on brew

you're done, next time you open any dir using nvim ., lazy will load all plugins

you can have alias v for nvim .

TODO: add gnu stow for dotfiles

for ghostty or any other term:
echo "export TERM=xterm-256color" >> ~/.bashrc
source ~/.bashrc
