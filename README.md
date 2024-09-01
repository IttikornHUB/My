local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

OrionLib:MakeNotification({
	Name = "สคริปที่กูต้องใช้",
	Content = "อ่านหาพ่อง",
	Image = "rbxassetid://4483345998",
	Time = 10
})


local Window = OrionLib:MakeWindow({Name = "ALL MY Scipy", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})



local Tab = Window:MakeTab({
	Name = "Cframe",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "COPYCFRAME",
	Callback = function()
      		setclipboard(tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame))
  	end    
})



local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "GhostHub(กด1รอบพอ)",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
  	end    
})


Tab:AddButton({
	Name = "RimuraHub(กด1รอบพอ)",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/RimuraHub/MAP/main/AllMAP"))()
  	end    
})


Tab:AddButton({
	Name = "Infiniteyield(กด1รอบพอ)",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
})
