# RPlusPlus
Custom made programming language inside Roblox Studio using roblox's core features to assemble an programming language inside roblox.

local MODULE = game:GetService("ServerScriptService"):WaitForChild("R++"):FindFirstChild("LanguageCore")
local RMODULE = require(MODULE)
table.insert(RMODULE.World.WorldScriptService,script.Name)
```lua
script.Parent.Run.MouseButton1Down:Connect(function()
	-- // LAUNCH USER
	RMODULE.LaunchUser()
	-- // MAIN
	
end)
```
