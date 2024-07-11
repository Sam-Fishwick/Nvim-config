# NVim Config Files
--------------------------------------------------------------------------|----|

This repository houses my NeoVim configuration files written in Lua.

These files were written by me while following along with ThePrimeagen's tutorial 
video, ["0 to LSP: Neovim RC From Scratch"](https://www.youtube.com/watch?v=w7i4amO_zaE&t=287s).

Adjustments have been made over time so these files deviate from the tutorial 
in minor ways, including the switch of package manager from Packer.vim to 
Lazy.vim.

This repository should be git cloned to ~/AppData/local/ for windows machines, 
and ~/.config/ for Linux machines.

The Treesitter plugin will require a C compiler to function. I installed 
MinGW GCC with ```scoop install gcc``` on windows, and 
```sudo apt-get install build-essential``` on Ubuntu (WSL2).

To ensure [Lazy.vim](https://github.com/folke/lazy.nvim) is installed correctly, 
run the ```:checkhealth lazy``` command (lower-case: lazy) and follow any prompts,
then run ```:Lazy``` (Pascal-case: Lazy) to update and manage your packages.

To ensure you have the correct LSP/linters/formatters, run the ```:Mason``` 
command and install as necessary.
