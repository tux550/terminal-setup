# Terminal Setup

## Install
Install zsh
```
sudo apt install zsh
```

Install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Install powerline fonts
```
sudo apt-get install fonts-powerline
```

Install powerline10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

Copy .zshrc and .p10k,zsh config files from repo to home
