# NewHub
NewHub
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Key Select", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
_G.Key = "Hello"
_G.KeyInput = string
function MakeScriptHub()
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Tổng Hợp Hack", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345978",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Auto Farm Chest",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/onepicesenpai/onepicesenpai/main/AutochestHub'))()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Best Farm level",
	Icon = "rbxassetid://4483545998",
	PremiumOnly = false
	})
Tab:AddButton({
	Name = "SnowHub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/ZPSXHUB/Hub/main/SnowHub-BloxFruit'))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "MtrietHub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "DomadicHub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "AdelHub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AdelOnTheTop/Adel-Hub/main/Main.lua"))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "mysticHub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/ZoiIntra/Dec/main/mystichub'))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "SonicHub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NickelHUBB/SonicTuru/main/Protected-25.lua"))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "Loli con Hub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/onepicesenpai/onepicesenpai/main/onichanokaka'))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "Lửa Chùa Hub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Padupo/scrnohop/main/FreeFrai'))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = " Con cặc",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Tulam2000/Min/main/Mindeptrai"))()
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "HuyDzVlerXD",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/Xeter"))()
      		print("button pressed")
  	end    
})
end
local Tab = Window:MakeTab({
	Name = "Key",
	Icon = "rbxassetid://4483345958",
	PremiumOnly = false
})
Tab:AddTextbox({
	Name = "EnterKey",
	Default = "default box input",
	TextDisappear = true,
	Callback = function(Value)
		_G.KeyInput = Value
	end	  
})
Tab:AddButton({
	Name = "Check Key",
	Callback = function()
      		if _G.KeyInput == _G.Key then
    MakeScriptHub()
  	end    
end
})
OrionLib:Init()
