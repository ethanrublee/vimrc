ethan's vim configuration
-------------------------

Configuration for my vim...

Try::

  if [ -e ~/.vim ] ; then
    mv ~/.vim ~/vim.bak
  fi
  git clone --recursive git://github.com/ethanrublee/vimrc.git ~/.vim 
  cd ~/.vim
  ./init.sh

