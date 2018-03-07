Install:

#Clone into
git clone git://github.com/biocarl/vimrc.git ~/.config/nvim

#Install Plug
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

#Install plugins
vim
>:PlugInstall

#Check dependencies
vim
>:CheckHealth #until everything is working
