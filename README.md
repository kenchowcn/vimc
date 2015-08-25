This is my Vim configuration, and it was from another vimer, I usually use Emacs as my editor, but Emacs can't replace of Vim in some situations, and I really can't bear the default configration of Vim, So I will change it as I want when I'm going to possess that machine everytime, this is called "revolution".

##Recipe
####Step 1
	mv ~/.vim ~/.vim_bk; mv ~/.vimrc ~/.vim_bk/; git clone https://github.com/kenchowcn/vimc.git ~/.vim/vimc && git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle && ln -s ~/.vim/vimc/vimrc ~/.vimrc && echo "Install success Step 1."

####Step 2
1. Running Vim
2. Execute ":BundleInstall"
