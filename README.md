# ColoredPrintsLib

## A Library that allows you output colored Prints (Like luarmor loading api)

# How to REQUIRE() ?
```lua
local PrintLibCode = game:HttpGet("https://raw.githubusercontent.com/Underssky/ColoredPrintsLib/refs/heads/main/ColorPrintLibrary.luau")
local PrintLib = loadstring(PrintLibCode)()
```

# How to USE?

- Colored print
```lua
PrintLib.CPrint(string, color)
```

- Rainbow print (rainbow speed)
```lua
PrintLib.RPrint(string, speed)
```

- Tween Color Switch 
```lua
PrintLib.SPrint(string, speed, color1 - ∞)
```

- Instant Color Switch 
```lua
PrintLib.SIPrint(string, speed, color1 - ∞)
```

-  Tween Gradient
```lua
PrintLib.GPrint(string, speed, col1 - ∞)
```

- Static Gradient
```lua
PrintLib.GSPrint(string, 0, col1 - ∞)
```
