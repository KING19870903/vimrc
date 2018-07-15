vimrc
=====

my vim configuration
### How to install
    #下载安装包
    git clone https://github.com/kingzs70/vimrc.git ~/
    
    # 替换本机配置文件
    cp ~/vimrc/vimrc ~/.vimrc
    
    # 安装Vundle插件
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

    mkdir -p ~/.vim/syntax
    cp -rf ~/vimrc/syntax/* ~/.vim/syntax

open VIM, then run

    :BundleInstall
