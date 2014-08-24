# vim-foldfocus #

## What is it? ##

vim-foldfocus is a vim plugin that extracts the text from the current fold level and outputs it into a new temporary buffer.

The ideia behind this plugin is to separate an important piece of code in to its own context (buffer). This is useful when you are trying to understand better a function or a particular piece of code, and you want to be able to search words using ```/```, ```*```, ```#``` without leaving the context of the code that you are exploring.

## Screenshots ##

![Screenshot](images/ff2.gif)
![Screenshot](images/ff3.gif)
![Screenshot](images/foldfocus1.gif)

## Installation ##

Using vundle, add this to your .vimrc:

```
Bundle 'vasconcelloslf/vim-foldfocus'
```

Than run:

```
:BundleInstall
```

## Usage ##

All you have to do is to map the function to a key of your choice. Here I use:

```vimscript
map <Leader>ff :call FoldFocus()<CR>
```

## About

Follow-me! [@vasconcelloslf](http://twitter.com/vasconcelloslf)

[http://luisvasconcellos.com](http://www.luisvasconcellos.com)
