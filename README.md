# A Neovim Plugin Template

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ellisonleao/nvim-plugin-template/default.yml?branch=main&style=for-the-badge)
![Lua](https://img.shields.io/badge/Made%20with%20Lua-blueviolet.svg?style=for-the-badge&logo=lua)


A template repository for Neovim plugins.

## Using it

Via `gh`:

```
$ gh repo create my-plugin -p ellisonleao/nvim-plugin-template
```

Via github web page:

Click on `Use this template`

![](https://docs.github.com/assets/cb-36544/images/help/repository/use-this-template-button.png)

## Features and structure

- 100% Lua
- Github actions to run tests and check for formatting errors (Stylua)
- Tests created with [busted](https://olivinelabs.com/busted/) + [plenary.nvim](https://github.com/nvim-lua/plenary.nvim)

### Plugin structure

```
.
├── lua
│   ├── nvim_uvm_log_highlight
│   │   └── module.lua
│   └── nvim_uvm_log_highlight.lua
├── Makefile
├── plugin
│   └── nvim_uvm_log_highlight.lua
├── README.md
├── tests
│   ├── minimal_init.lua
│   └── nvim_uvm_log_highlight
│       └── nvim_uvm_log_highlight_spec.lua
```
