# A Nice Key System UI Library made by Fear_God
**This is made by Fear_God, Copying or Skidding will take you down.**

***Loader:***
```lua
local UI = loadstring(game:HttpGet("https://raw.githubusercontent.com/memejames2/Key-System-UI-Roblox/main/UI.lua"))()
```
***Create Window***
```lua
local Window = UI:CreateMain("Name") -- [1] String; Name
```
***Create Key Input***
```lua
Window:KeyInput("Text", "Insert Key", function(txt) -- [1] String; Text, [2] String; PlaceHolder
    getgenv().Input = txt
end)
```
***Create Check Key***
```lua
Window:CheckKey("Check Key", function() -- [1] String; Name
    print("HI")
end)
```

***Create Get Key***
```lua
Window:GetKey("Check Key", function() -- [1] String; Name
    print("HI")
end)
```
