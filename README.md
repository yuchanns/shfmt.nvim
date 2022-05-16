# shfmt.nvim
shfmt plugin for nvim.

## Installation
* Neovim >= 0.7.0
* shfmt

### [packer.nvim](https://github.com/wbthomason/packer.nvim)
```lua
use "yuchanns/shfmt.nvim"
```

## Usage
### Configuration
```lua
require("shfmt").setup({
  -- Default configs
  cmd = "shfmt",
  args = { "-l", "-w" },
  auto_format = false,
})
```
### Manual Format
```lua
-- using lua function
: lua require("shfmt").formatting()
```

## Contributing
Bug reports and feature requests are welcome! Feel free to make PRs!
