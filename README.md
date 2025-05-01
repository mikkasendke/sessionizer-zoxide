# sessionizer-zoxide
A basic generator for [sessionizer.wezterm](https://github.com/mikkasendke/sessionizer.wezterm) that returns zoxide results.

## Usage
1. Require the plugin
```lua
local zoxide = wezterm.plugin.require "https://github.com/mikkasendke/sessionizer-zoxide.git"
```
2. Use it in your schema
```lua
local my_schema = {
  -- ... other stuff
  zoxide.Zoxide {},
  -- other stuff ...
}
```
Alternatively just use it directly when requiring like this:
```lua
local my_schema = {
  -- ... other stuff
  wezterm.plugin.require "https://github.com/mikkasendke/sessionizer-zoxide.git".Zoxide {},
  -- other stuff ...
}
```

done :)
