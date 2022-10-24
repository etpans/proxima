# Proxima Documentation
Documentation for Proxima UI library.

## Calling the library
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/2kbyte/proxima/main/source.lua")()
```

## Creating a Tab
```lua
local Tab = library:AddTab(<string> Name, <number> Position)
```

## Creating a Column
```lua
local Column1 = Tab:AddColumn()
local Column2 = Tab:AddColumn()
```
Each tab can contain two columns that are created using the same function.

## Creating a Section
```lua
local Section = Column1:AddSection(<string> Name)
```

## Creating a Label
```lua
Column1:AddLabel(<string> Name)
```

## Creating a Divider
```lua
Column1:AddDivider(<string> Name)
```
## Example
TBA
