`1. Setting up Zsh: 
    a. Check your shell: echo $SHELL
    b. To install sudo apt install Zsh
    c. sudo chsh to change shell
    d. Change shell from /bin/bash to /bin/zsh
    e. Set up blank .zshrc
2. Setting up Oh-My-Zsh
    a. go to: `https://github.com/ohmyzsh/ohmyzsh
    b. Check for curl/wget/fetch (which <command>)
    c. Download and check that .zshrc has set up
3. Setting up zsh-autosuggestions:
    a. go to : https://github.com/zsh-users/zsh-autosuggestions
    b. git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    c. In the plugins section, add zsh-autosuggestions
4. ZSH syntax highlighing
    a. go to: https://github.com/zsh-users/zsh-syntax-highlighting
    b. git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    c. in the plugin section add zsh-syntax-highlighing
5. Powerlevel10k
    a. go to: https://github.com/romkatv/powerlevel10k
    b. run: git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
    c. Set the ZSH_THEME="powerlevel10k/powerlevel10k" in ~/.zshrc
    d. Follow the prompts
6. Install TMUX
    a. sudo apt install tmux
    b. copy .tmux.conf from this repository
