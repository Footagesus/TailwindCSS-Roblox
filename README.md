# Tailwindcss-Roblox

## How to use Colors.lua:
### 1. Connect Colors.lua (loadstring)
```lua
local ColorsLoadstring = loadstring(game:HttpGet("https://raw.githubusercontent.com/Footagesus/TailwindCSS-Roblox/main/colors.luau"))()
```
### 2. Using
```lua
local ColorsLoadstring = loadstring(game:HttpGet("https://raw.githubusercontent.com/Footagesus/TailwindCSS-Roblox/main/colors.luau"))()

local GreenRGB = ColorsLoadstring.green["500"].RGB -- RGB
myFrame.BackgroundColor3 = GreenRGB

local GreenHEX = ColorsLoadstring.green["500"].hex
print(Green)
```

Credits: TailwindCSS
