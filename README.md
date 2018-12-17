# cuilei_dotfiles

把`~/dotfiles`文件夹里的配置文件映射到用户目录。
`ln -s ~/dotfiles/zshrc ~/.zshrc`

## vim
vim安装
- git clone `https://github.com/barretlee/autoconfig-mac-vimrc`
- cd autoconfig-mac-vimrc
- chmod +x install
- ./install

安装之后出现的文件夹`~/.vim`，配置文件`~/.vimrc`。

## spacemacs
安装emacs
`brew cask install emacs`

安装emacs配置文件 spacemacs
`git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d`

安装之后出现的文件夹`~/.emacs.d`，配置文件`~/.spacemacs`。

## zsh

iterm zsh theme自定义
https://github.com/wesbos/Cobalt2-iterm

## mackup统一备份到dropbox

https://github.com/lra/mackup

## 终极策略
mac Time Machine + NAS
使用Time Machine，你既可以回到过去某个时刻，提取某个文件在当时的版本；也可以在电脑异常崩溃后直接全盘恢复到过去某个时刻的状态。