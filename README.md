
###What is this?
This repo contains my personal terminal configuration settings and related files. I am making this so that its easy for me to get my setup running on a new machine. (I hate ) 

###Can I use it?
Yeah feel free to use it, make sure you change the user details in the dotfiles.

###Initial setup:
I use a OSX so this assumes no other special config other than the default settings that you already have after installing OSX.

##Setup:

* Zsh & oh-my-zsh Installation:
  
   1. `sudo apt-get install zsh`
   2. Make it your default shell: `chsh -s $(which zsh)`
   3. Make sure it worked: `echo $SHELL`. Expected result: `/bin/zsh`
   Now let's install oh-my-zsh
   4. Using curl: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
   5. Use the .zshrc file
   
