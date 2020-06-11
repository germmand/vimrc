# My .vimrc configuration

Hi! This is where I store my .vimrc configuration. I'm going to keep adding as much things as I find interesting and also improve my workflow. But at the same time I'm going to try to keep it minimal and simple.

That's it.

### Prerequisites 📋

There's quite a few things you need to have installed for this configuration to work:

* Vim (duh) - Although it has to be >= 8.0.1453 (Version).
* [NodeJS (>= 10.12)](https://nodejs.org/es/) - This is due to the [Coc.nvim](https://github.com/neoclide/coc.nvim) plugin.
* [Vim-Plug](https://github.com/junegunn/vim-plug) - The plugin manager

### Installing 🔧

1. Clone the repository:
```
$ git clone git@github.com:germmand/vimrc.git germmand-vimrc && cd germmand-vimrc
```

2. Copy and paste the `.vimrc` file to your home folder.
3. Open vim and execute: 
```vimrc
:PlugInstall
```
4. Once it's done, you can add completion to your language/s of choice  through:
```vimrc
:CocInstall coc-go coc-python
```
For more information about this, check out [Coc Extensions](https://github.com/neoclide/coc.nvim/wiki/Using-coc-extensions).

For generic web-development consider: 
```vimrc
:CocInstall coc-tsserver coc-json coc-html coc-css
```

## License 📄

This project is under the license (MIT) - take a look at the [LICENSE.md](LICENSE.md) file for more details.
