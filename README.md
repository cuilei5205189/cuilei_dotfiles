# cuilei_dotfiles

把`~/dotfiles`文件夹里的配置文件映射到用户目录。
`$ ln -s ~/dotfiles/zshrc ~/.zshrc`

## vim
vim安装
```bash
$ git clone https://github.com/barretlee/autoconfig-mac-vimrc
$ cd autoconfig-mac-vimrc
$ chmod +x install
$ ./install
```

安装之后出现的文件夹`~/.vim`，配置文件`~/.vimrc`。

## spacemacs
安装emacs
`$ brew cask install emacs`

安装emacs配置文件 spacemacs
`$ git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d`

安装之后出现的文件夹`~/.emacs.d`，配置文件`~/.spacemacs`。

## zsh

### ~/.zsh文件夹修改
```
./custom/plugin
custom/plugins
├── example
├── git-open
├── zsh-autosuggestions
└── zsh-syntax-highlighting
custom/themes
└──themes
   └── cobalt2.zsh-theme
cobalt2.zsh-theme
```
iterm zsh theme自定义
https://github.com/wesbos/Cobalt2-iterm

其他文件以官方库为准
https://github.com/robbyrussell/oh-my-zsh

ohmyzsh更新命令
`$ upgrade_oh_my_zsh`

### zsh配置文件
具体配置在cuilei_dotfiles
`zshrc`

### zsh theme
https://github.com/bhilburn/powerlevel9k
https://nerdfonts.com/
https://github.com/athityakumar/colorls

#### zsh插件
```
plugins=(
  git zsh-autosuggestions dirhistory fzf zsh-syntax-highlighting git-open osx rails ruby
)
```

## mackup统一备份到dropbox
https://github.com/lra/mackup

## 终极策略
mac Time Machine + NAS
使用Time Machine，你既可以回到过去某个时刻，提取某个文件在当时的版本；也可以在电脑异常崩溃后直接全盘恢复到过去某个时刻的状态。
