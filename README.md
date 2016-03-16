#My vim/tmux configuration

ln -s ~/.vim/vimrc ~/.vimrc
ln -s ~/.vim/tmux.conf ~/.tmux.conf

Install powerline font in order to use the powerline symbols in the airline theme

git clone https://github.com/powerline/fonts.git
cd fonts
sudo ./install

change the terminal profile to use font "Ubuntu mono derivative powerline"

enforce tmux 256 terminal option
echo "alias tmux='tmux -2'" >> ~/.bash_aliases
source ~/.bash_aliases