# wsl2-dotfiles_bare
Dotfiles for my home configuration under WSL2. This only contains no desktop configs.

Steps in setting up this repo in a new machine:
1. Install git
2. 
	> git config --global user.name "dyharlan"
	> git config --global user.email "dyharlan45@gmail.com"
	> git config --global color.ui true
	> git config --global core.editor nano
	> ssh-keygen -t rsa -C "dyharlan45@gmail.com"

3. Copy contents of rsa file to clipboard, then paste to github user settings
4. To test type
	> ssh -T git@github.com
5. init home directory:
	> git init
6. add dotfile repo:
	> git remote add wsl2-dotfiles_bare 'https://github.com/dyharlan/wsl2-dotfiles_bare.git'
7. pull changes from remote:
	> git pull wsl2-dotfiles_bare main

In pushing files:
1. > git add -all
2. > git commit -m "YOUR_MESSAGE"
3. > git push mainrepo main
