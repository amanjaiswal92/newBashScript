# newBashScript
Change your shell to zsh:

sudo apt-get

sudo apt-get install zsh git-core wget

wget https://github.com/ -O - | zsh

echo "/usr/bin/zsh" >> ~/.bashrc 


Restart terminal

Set up git aliases:
   vi ~/.zshrc
add the following lines:

export GIT_SSL_NO_VERIFY=true
alias gst='git status '

alias ga='git add '

alias gb='git branch '

alias gc='git commit '

alias gd='git diff '

alias gco='git checkout '

alias ggpush='git push origin HEAD'

alias ggpull='git pull origin HEAD' 

save the file

source ~/.zshrc
   
Configure git to store password:
    git config  --global credential.helper store
