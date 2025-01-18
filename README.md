**This repo is supposed to used as config by NvChad users!**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
- So you can delete the .git from this repo ( when you clone it locally ) or fork it :)

# Credits

1) Lazyvim starter https://github.com/LazyVim/starter as nvchad's starter was inspired by Lazyvim's . It made a lot of things easier!


Pre-requisites

    Neovim 0.10.
    Nerd Font as your terminal font.
        Make sure the nerd font you set doesn't end with Mono to prevent small icons.
        Example : JetbrainsMono Nerd Font and not JetbrainsMono Nerd Font Mono
    Ripgrep is required for grep searching with Telescope (OPTIONAL).
    GCC, Windows users must have mingw installed and set on path.
    Make, Windows users must have GnuWin32 installed and set on path.
    Delete old neovim folders (check commands below)

Install

git clone https://github.com/kheshav/nvchad_config.git ~/.config/nvim && nvim
