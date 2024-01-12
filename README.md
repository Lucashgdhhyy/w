local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Lk Hub|Scripts Hub V0.5", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Credits",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
OrionLib:MakeNotification({
	Name = "LK HUB | Hubs scripts",
	Content = "Script Hub",
	Image = "rbxassetid://4483345998",
	Time = 5
})
Tab:AddButton({
	Name = "Hub | orion library",
	Callback = function()     
	      		print("button pressed")
  	end    
})
Tab:AddButton({
	Name = "By LK Teamer S2",
	Callback = function()  
      		print("button pressed") 
     end
})

local Tab = Window:MakeTab({
	Name = "blade ball hubs",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Bedol Hub",
	Callback = function()  
      		print("button pressed")      loadstring(game:HttpGet('https://raw.githubusercontent.com/nqxlOfc/Loaders/main/Blade_Ball.lua'))() 
    end
})
Tab:AddButton({
	Name = "Twilight ",
	Callback = function()  
      		print("button pressed")   loadstring(game:HttpGet('https://raw.githubusercontent.com/0x1s2s/twilightxd/main/twilightlol'))()   
    end
})

local Tab = Window:MakeTab({
	Name = "blox fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()  
      		print("button pressed")    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
    end
})

local Tab = Window:MakeTab({
	Name = "bypass anti cheat",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Bypass🛡️🛡️",
	Callback = function()  
      		print("button pressed")    
    end
})

local Tab = Window:MakeTab({
	Name = "Pet simulator 99",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Redz Hub(no key)",
	Callback = function()  
      		print("button pressed")    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()
    end
})

local Tab = Window:MakeTab({
	Name = "CMDS Admins",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
	})
	
Tab:AddButton({
	Name = "Infinity yield",
	Callback = function()  
      		print("button pressed")   loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    end
})

local Tab = Window:MakeTab({
	Name = "Menssage",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
	})
	
	Tab:AddButton({
	Name = "sub on my channel",
	Callback = function()  
      		print("button pressed")  
    end
})

Tab:AddButton({
	Name = "lucashelomanu",
	Callback = function()  
      		print("button pressed")   
    end
})
-- Dropdown:Refresh(List<table>,true)
--Dropdown:Set("dropdown option")
OrionLib:Init()
-- destroying the interface: OrionLib:Destroy() 
