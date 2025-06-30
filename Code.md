# 🧊 Ice Hub Lib

Ice Hub Lib is a library of the  old ice hub we know which contains in its library (label, textbox, toggle, dropdown, button).

---

## Lib

```lua
local IceHub = loadstring(game:HttpGet("https://raw.githubusercontent.com/<user>/IceHub/main/icehub.lua"))()
```

---

## CreateMain()
```lua
local MainUI = IceHub.CreateMain()
-- Profile, credits
-- Main Body
```
## Tab
```lua
local Tab_test1 = MainUI:NewTab("test1")
local test1 = Tab_test1:NewSection("test1")
```
## Label
```lua
test1:NewLabel("Label1")
```
## TextBox
```lua
test1:NewTextBox("Text", "", function(value)
    print("Selected: ", value)
end)
```
## Toggle
```lua
test1:NewToggle("Toggle", function(v)
    print("Toggle: ", v)
end)
```
DropDown
```lua
test1:NewDropdown("Dropdown", {
    "1", "2", "3"
}, function(v)
    print("Wybrano:", v)
end)
```
## Button
```lua
test1:NewButton("Button", function()
    print("Click Me!")
end)
```
## Image
```lua
test1:NewTutorial(123456789)
```
