# nginx.vim

## Description

[Vim](http://www.vim.org/) plugin for [Nginx](http://www.nginx.org)

This is a clone from: <br>
https://github.com/nginx/nginx/tree/master/contrib/vim

## File structure
* Mostly updated file: syntax/nginx.vim
  * current version
    * https://github.com/nginx/nginx/blob/release-1.18.0/contrib/vim/syntax/nginx.vim

```bash
nginx.vim/
├── ftdetect
│   └── nginx.vim
├── ftplugin
│   └── nginx.vim
├── indent
│   └── nginx.vim
└── syntax
    └── nginx.vim
```

## Installation

Install using any vim plugin manager. If you're not familiar with any, go with Plug ([``vim-plug``](https://github.com/junegunn/vim-plug)).
Then install this plugin using the your vim's plugin manager as follows:

### Pathogen
```
git clone https://github.com/charlietag/nginx.vim.git ~/.vim/bundle/nginx.vim
```

### Plug
```
Plug 'charlietag/nginx.vim'
```

### Dein.vim
```
call dein#add('charlietag/nginx.vim')
```

### Vundle
```
Plugin 'charlietag/nginx.vim'
```
