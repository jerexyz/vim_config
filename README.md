### install `vim-pathogen`

```
mkdir ~/.vim/bundle && cd ~/.vim
git subtree add --prefix=bundle/vim-pathogen git@github.com:tpope/vim-pathogen.git master
git subtree add --prefix bundle/vim-airline git@github.com:vim-airline/vim-airline.git master
git subtree add --prefix bundle/vim-airline-theme git@github.com:vim-airline/vim-airline-theme.git master
```