# RPlusPlus
Custom made programming language inside Roblox Studio using roblox's core features to assemble an programming language inside roblox.

# Instructions
1. Download the "Language.rbxl" file from the repository
2. Open it
3. Go to StarterGUI
4. Open the GUI named "Console"
5. Open the Script named "Main" and start editing!

# Services

World - Contains everything

World:

  -- WorldScriptService
  
  -- WorldInstanceService
  
  -- WorldConsoleService
  
  -- WorldUIService
  

# Mathematical Operation Strings
"x" "Multiply"
"-" "Divide"
"+" "Plus"
"-" "Minus"

# Functions
RMODULE.WriteString("String")

RMODULE.WriteError("String")

RMODULE.WriteWarning("String")

RMODULE.CreatePart(Size_Vector3,Position_Vector3,Brickcolor,AnchoredBool,CanCollideBool,"NameString")

RMODULE.InsertPreset("Name")

RMODULE.CreatePartsFromTable(Table)

RMODULE.RequireLibrary("LibraryName")

RMODULE.CreateWindow(SizeUDIM2,PositionUDIM2,ColorBRICK,Name)

RMODULE.Demolish(Directory,Service)

RMODULE.WriteEnter(Content,PlaceholderTextOption,ClearTextOnFocusOption)

RMODULE.WriteCalculate(Num1,Operation,Num2)

RMODULE.SetVector3(Name,Type,Vector3Value)

RMODULE.SetProperty(Name,Type,Value)

RMODULE.SetUDim2(Name,Type,UDim2Value)

RMODULE.LaunchUser()

RMODULE.Shutdown()


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
