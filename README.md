# Fleet theme for Neovim

A port of the default theme from Jetbrains' Fleet IDE for Neovim with Treesitter support.

<img width="2034" alt="Screenshot" src="https://github.com/user-attachments/assets/3b28ede8-a963-4abe-83e4-1fd9975cc5c7">

Includes support for:
- Tree-sitter
- LSP semantic highlighting
- [HiPhish/nvim-ts-rainbow2](https://github.com/HiPhish/nvim-ts-rainbow2)
- [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
  "felipeagc/fleet-theme-nvim",
  config = function() vim.cmd("colorscheme fleet") end
}
```

## Credits

Colors were initially taken from the [Helix editor](https://github.com/helix-editor/helix)'s builtin [fleet dark theme](https://github.com/helix-editor/helix/blob/b0ceac608ebc117399af89b81fbd0837d370161d/runtime/themes/fleet_dark.toml).

## License
[MIT](./LICENSE)
