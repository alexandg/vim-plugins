Vim Plugins
---------------

Collection of submodules for Vim plugins. Loaded via Pathogen.

### Dependencies

* Exuberant ctags
* pep8
* autopep8
* python3-jedi

### To Install

```
cd ~/.vim
git clone https://github.com/alexandg/vim-plugins.git bundle
git submodule init
git submodule update
```

### To Update plugins

```
cd ~/.vim/bundle
git submodule foreach git pull
```
