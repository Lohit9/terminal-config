
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
   
* To use agnoster theme (my favourite):
  1. change the theme in the .zshrc file
  2. Install powerline fonts : https://github.com/powerline/fonts
  3. To check if it works use: `echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"` and make sure you see valid symbols

_WIP_: The issue now is to figure out how to shorten the path to make it all more readable. Make the absolute path into relative path.
   
