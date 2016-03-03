# dotfiles
My shell config files based on [this](https://developer.atlassian.com/blog/2016/02/best-way-to-store-dotfiles-git-bare-repo/) excellent approach

# Add new files 
```
config status
config add .vimrc
config commit -m "Add vimrc"
config add .bashrc
config commit -m "Add bashrc"
config push
```

# Install on a new machine
```
curl -Lks https://goo.gl/CPFSgo | /bin/bash
```
