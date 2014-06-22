dotzsh: My zsh configuration.

Installation:

    git clone git://github.com/frankjmattia/dotzsh.git ~/.zsh

Create symlinks:

    ln -s ~/.zsh/zshrc ~/.zshrc
    ln -s ~/.zsh/zshenv ~/.zshenv
    ln -s ~/.zsh/zlogin ~/.zlogin

Put sensitive environement variables somewhere else:

    touch ~/.zshenvp
    $EDITOR ~/.zshenvp
