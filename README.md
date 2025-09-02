# Ras
Ras is neovim theme inspired by raise a suilen which is a band of Bangdream.

# Installation
You can use lazy.nvim to install it as follows:
```lua
{
  {
    "Acomage/ras",
    dependencies = { "tjdevries/colorbuddy.nvim" },
    lazy = false,
    priority = 1000,
  },
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "ras",
    },
  },
}
```
