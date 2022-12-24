# my-zsh

Clone this repo first 

`git clone https://github.com/andysmithfal/my-zsh.git ~/.zshrepo`

Link .zshrc 

`ln -s ~/.zshrepo/.zshrc ~/.zshrc`

Install zsh (if req'd)

`sudo apt install zsh`

Set zsh as default shell

`chsh -s $(which zsh)`

Install oh my zsh

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

Link custom folder
```
rm -rf ~/.oh-my-zsh/custom
ln -s ~/.zshrepo/custom ~/.oh-my-zsh
```

Other things to install: 

- [bat](https://github.com/sharkdp/bat)
- [thefuck](https://github.com/nvbn/thefuck)
- [p10k font](https://github.com/romkatv/powerlevel10k#fonts)
