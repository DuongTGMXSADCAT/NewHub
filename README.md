local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Key Select", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
_G.Key = "ebkuqwj598"
_G.KeyInput = string
function MakeScriptHub()
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Tổng Hợp Hack", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://12235359506"
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
	Name = " Min Depzai Hub",
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
Tab:AddButton({
	Name = "Sara Hub",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/SaraSenpai/bloxfruist/main/Sarahub'))()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Race V4",
	Icon = "rbxassetid://12235359506"
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Baki Hub",
	Callback = function()
      		repeat wait() until game:IsLoaded() and game.Players.LocalPlayer
loadstring(game:HttpGet("https://raw.githubusercontent.com/memaybeohub/Function-Scripts/main/YMFHUB_MISC.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Mtriet Hub",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Hirimi Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Hirimii/HirimiHub/main/LoaderScript.lua"))()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Auto Bounty",
	Icon = "rbxassetid://12235359506"
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Magma + Dragon Talon",
	Callback = function()
      		getgenv().Key = 'Key Here'
repeat wait()
until game:IsLoaded()
wait()
local TableChat = {"I <3 Banana So Much","I'm Banana huhuhu"}
spawn(function()
    while wait() do 
        pcall(function()
            game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(TableChat[math.random(1,#TableChat)],"All")
            wait(45)
        end)
    end
end)
getgenv().Setting = {
    ["Team"] = "Pirates", --Marines,Pirates
    ["Webhook"] = {
        ["Enabled"] = true,
        ["Url Webhook"] = "Webhook Here", --Your Url
    },
    ["Misc"] = {
        ["AutoBuyRandomandStoreFruit"] = true,
        ["AutoBuySurprise"] = true,
    },
    ["Click"] = {
        ["Enable"] = false,
        ["Click Gun"] = false,
        ["OnLowHealthDisable"] = false,
        ["LowHealth"] = 4500,
    },
    ["SafeZone"] = {
        ["Enable"] = true,
        ["LowHealth"] = 4500,
        ["MaxHealth"] = 5000,
        ["Teleport Y"] = 2000
    },
    ["Race V4"] = {
        ["Enable"] = true,
    },
    ["Invisible"] = true,
    ["White Screen"] = false,
    ["GunMethod"] = false, --Support Only Melee And Gun,Not Invisible, Turn On Enabled Gun and Melee Please
    ["SpamSkill"] = false, -- Will use all skills as fast as possbile ignore holding skills
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
               [ "X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
            },
        },
        ["Blox Fruit"] = {
            ["Enable"] = true,
            ["Delay"] = 2.5,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 2,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.3,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.3,
                },
                ["V"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.3,
                },
                ["F"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Gun"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Sword"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
    }
}
repeat wait() until game:IsLoaded() and game.Players.LocalPlayer
spawn(function()
	while wait() do
			game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(child)
				if child.Name == 'ErrorPrompt' and child:FindFirstChild('MessageArea') and child.MessageArea:FindFirstChild("ErrorFrame") then
					game:GetService("TeleportService"):Teleport(game.PlaceId)
				end
			end)
		end
	end)
loadstring(game:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BountyShit.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Dragon Talon + Venom",
	Callback = function()
      		getgenv().Key = 'Key Here'
repeat wait()
until game:IsLoaded()
wait()
local TableChat = {"I <3 Banana So Much","I'm Banana huhuhu"}
spawn(function()
    while wait() do 
        pcall(function()
            game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(TableChat[math.random(1,#TableChat)],"All")
            wait(45)
        end)
    end
end)
getgenv().Setting = {
    ["Team"] = "Pirates", --Marines,Pirates
    ["Webhook"] = {
        ["Enabled"] = true,
        ["Url Webhook"] = "Webhook Here", --Your Url
    },
    ["Misc"] = {
        ["AutoBuyRandomandStoreFruit"] = true,
        ["AutoBuySurprise"] = true,
    },
    ["Click"] = {
        ["Enable"] = false,
        ["Click Gun"] = false,
        ["OnLowHealthDisable"] = false,
        ["LowHealth"] = 4500,
    },
    ["SafeZone"] = {
        ["Enable"] = true,
        ["LowHealth"] = 4500,
        ["MaxHealth"] = 5000,
        ["Teleport Y"] = 2000
    },
    ["Race V4"] = {
        ["Enable"] = true,
    },
    ["Invisible"] = true,
    ["White Screen"] = false,
    ["GunMethod"] = false, --Support Only Melee And Gun,Not Invisible, Turn On Enabled Gun and Melee Please
    ["SpamSkill"] = false, -- Will use all skills as fast as possbile ignore holding skills
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
               [ "X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
            },
        },
        ["Blox Fruit"] = {
            ["Enable"] = true,
            ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 2,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["V"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                },
                ["F"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
            },
        },
        ["Gun"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Sword"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
    }
}
repeat wait() until game:IsLoaded() and game.Players.LocalPlayer
spawn(function()
	while wait() do
			game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(child)
				if child.Name == 'ErrorPrompt' and child:FindFirstChild('MessageArea') and child.MessageArea:FindFirstChild("ErrorFrame") then
					game:GetService("TeleportService"):Teleport(game.PlaceId)
				end
			end)
		end
	end)
loadstring(game:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BountyShit.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Dragon Talon + Acid",
	Callback = function()
      		getgenv().Key = 'Key Here'
repeat wait()
until game:IsLoaded()
wait()
local TableChat = {"I <3 Banana So Much","I'm Banana huhuhu"}
spawn(function()
    while wait() do 
        pcall(function()
            game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(TableChat[math.random(1,#TableChat)],"All")
            wait(45)
        end)
    end
end)
getgenv().Setting = {
    ["Team"] = "Pirates", --Marines,Pirates
    ["Webhook"] = {
        ["Enabled"] = true,
        ["Url Webhook"] = "Webhook Here", --Your Url
    },
    ["Misc"] = {
        ["AutoBuyRandomandStoreFruit"] = true,
        ["AutoBuySurprise"] = true,
    },
    ["Click"] = {
        ["Enable"] = true,
        ["Click Gun"] = true,
        ["OnLowHealthDisable"] = true,
        ["LowHealth"] = 4500,
    },
    ["SafeZone"] = {
        ["Enable"] = true,
        ["LowHealth"] = 4500,
        ["MaxHealth"] = 5000,
        ["Teleport Y"] = 2000
    },
    ["Race V4"] = {
        ["Enable"] = true,
    },
    ["Invisible"] = false,
    ["White Screen"] = false,
    ["GunMethod"] = true, --Support Only Melee And Gun,Not Invisible, Turn On Enabled Gun and Melee Please
    ["SpamSkill"] = false, -- Will use all skills as fast as possbile ignore holding skills
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
               [ "X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.6,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1.5,
                },
            },
        },
        ["Blox Fruit"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["V"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["F"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Gun"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.7,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.7,
                },
            },
        },
        ["Sword"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
    }
}
repeat wait() until game:IsLoaded() and game.Players.LocalPlayer
spawn(function()
	while wait() do
			game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(child)
				if child.Name == 'ErrorPrompt' and child:FindFirstChild('MessageArea') and child.MessageArea:FindFirstChild("ErrorFrame") then
					game:GetService("TeleportService"):Teleport(game.PlaceId)
				end
			end)
		end
	end)
loadstring(game:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BountyShit.lua"))()
  	end    
})
end
local Tab = Window:MakeTab({
	Name = "Key",
	Icon = "rbxassetid://12235359506"
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
