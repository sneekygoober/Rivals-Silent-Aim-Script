# Rivals-Silent-Aim-Script
Sorry to anyone wanting to view the source, I've obfuscated it so that the RIVALS developers don't patch this too quickly.
This script is not open-source. You can also view this script over at [scriptblox.com](https://scriptblox.com/script/RIVALS-Silent-Aim-Keyless-202191) or [haxhell.com](https://haxhell.com/scripts/rivals-rivals-silent-aim-keyless) or [rscripts.net](https://rscripts.net/script/rivals-silent-aim-keyless-e0jY).

```lua
local keybind = Enum.KeyCode.B;
getgenv().blatant = true;
getgenv().fov = 300;
(cloneref or function(i: Instance) return i; end)(game:GetService("UserInputService")).InputBegan:Connect(function(io, gp) if not gp and io.KeyCode == keybind then getgenv().blatant = not getgenv().blatant; end; end);

loadstring(game:HttpGet("https://raw.githubusercontent.com/sneekygoober/Rivals-Silent-Aim-Script/refs/heads/main/main.luau"))();
```
