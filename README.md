# zsh
My ZSH Config - forked from [ChrisTitusTech](https://github.com/ChrisTitusTech/zsh)

## Setup
```
cd ~/
git clone --recursive https://github.com/wizzdom/zsh
ln -s -f ~/zsh/.zshrc ~/.zshrc
```
## Get Dependencies 
  - **zsh** - *obviously!*
  - **zsh-syntax-highlighting** - syntax highlighting for ZSH in standard repos
  - **autojump** - jump to directories with j or jc for child or jo to open in file manager
  - **zsh-autosuggestions** - Suggestions based on your history
  
*powerlevel10k prompt is included as a git submodule (it will be downloaded as part of the git clone)* 
Finish the conversion by changing your user in /etc/passwd to /bin/zsh instead of /bin/bash
