# Environment Setup

### Xcode

  Install through App Store

### Xcode command line tools

        // terminal
        xcode-select --install

### Homebrew

        /*
         * Paste below at a Terminal prompt.
        */

        /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### iTerm2 - replace local Terminal

  [download](https://www.iterm2.com/)

### Zsh & oh my Zsh- shell

        // Check [here](https://github.com/robbyrussell/oh-my-zsh) for detail

        brew install zsh zsh-completions // install zsh

        sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)" // install oh my zsh

        //import current env variable into .zshrc after installation (安装完成后将当前的环境变量导入 .zshrc 中)

        echo "export PATH=$PATH" >> ~/.zshrc

        source ~/.zshrc

  plugins configuration for zsh

        // ~/.zshrc
        plugins=(git github git-flow git-extras brew osx node npm copydir copyfile cp sublime zsh-syntax-highlighting)

### Git

        brew install git

        // basic configuration
        git config --global user.name "Your Name"
        git config --global user.email "your_email@youremail.com"

        // if use ssh (如果使用 SSH 方式来拉取/推送代码), Check [here](https://help.github.com/articles/connecting-to-github-with-ssh/)
        // 而 HTTPS 方式如果不想每次都输入你的 Git 用户名和密码的话，请继续按照以下配置。

        git config --global credential.helper osxkeychain

### Node.js

  [download](https://nodejs.org/en/)

### Update npm version after install Node.js

        sudo npm up npm -g

### Atom - Editor

  [download](https://atom.io/)

  + plugins

    + angularjs
    + atom-beautify
    + autoclose-html
    + autocomplete-paths
    + busy-signal
    + color-picker
    + docblockr
    + emmet
    + expose
    + file-icons
    + git-plus
    + highlight-line
    + highlight-selected
    + intentions
    + linter
    + linter-jshint
    + linter-sass-lint
    + linter-ui-default
    + minimap
    + minimap-highlight-selected
    + pigments
    + project-manager

  + theme
    + atom-material-syntax
    + atom-material-ui
