# nvim-gotests

[gotests](https://github.com/cweill/gotests) wrapper for neovim

## Usage

Supported methods:

- Add test for single function

```lua
local gotests = require('nvim-gotests')

vim.keymap.set('n', '<leader>gat', function() gotests.fun_test() end, {})
```

This will generate unit test for function under cursor

