# RPlusPlus
Custom made programming language inside Roblox Studio using roblox's core features to assemble an programming language inside roblox.

# Main Script In The RBXL File
```lua
local MODULE = game:GetService("ServerScriptService"):WaitForChild("R++"):FindFirstChild("LanguageCore")
local RMODULE = require(MODULE)
table.insert(RMODULE.World.WorldScriptService,script.Name)

script.Parent.Run.MouseButton1Down:Connect(function()
	-- // LAUNCH USER
	RMODULE.LaunchUser()
	-- // MAIN
	
end)
```
