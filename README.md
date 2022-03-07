if game.CoreGui:FindFirstChild("Discord") then

    game.CoreGui:FindFirstChild("Discord"):Destroy()

end

if game.CoreGui:FindFirstChild("SOMEXHUBMODILE") then

    game.CoreGui:FindFirstChild("SOMEXHUBMODILE"):Destroy()

end

 wait(1)

local SOMEXHUBMODILE = Instance.new("ScreenGui")

local MODILEGUISOMEXHUB = Instance.new("TextButton")

local MODILEGUISOMEXHUBHUI = Instance.new("UICorner")

local MODILEMAGE = Instance.new("ImageLabel")

SOMEXHUBMODILE.Name = "SOMEXHUBMODILE"

SOMEXHUBMODILE.Parent = game.CoreGui

SOMEXHUBMODILE.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MODILEGUISOMEXHUB.Name = "MODILEGUISOMEXHUB"

MODILEGUISOMEXHUB.Parent = SOMEXHUBMODILE

MODILEGUISOMEXHUB.BackgroundColor3 = Color3.fromRGB(30,20,20)

MODILEGUISOMEXHUB.BorderSizePixel = 0

MODILEGUISOMEXHUB.Position = UDim2.new(0.120833337, 0, 0.0952890813, 0)

MODILEGUISOMEXHUB.Size = UDim2.new(0, 50, 0, 50)

MODILEGUISOMEXHUB.Font = Enum.Font.SourceSans

MODILEGUISOMEXHUB.Text = ""

MODILEGUISOMEXHUB.TextColor3 = Color3.fromRGB(0, 0, 0)

MODILEGUISOMEXHUB.TextSize = 14.000

MODILEGUISOMEXHUB.Draggable = true

MODILEGUISOMEXHUB.MouseButton1Click:Connect(function()

game.CoreGui:FindFirstChild("Discord").Enabled = not game.CoreGui:FindFirstChild("Discord").Enabled

end)

do

if game:GetService("CoreGui"):FindFirstChild("Discord") then

end

end

MODILEGUISOMEXHUBHUI.Name = "MODILEGUISOMEXHUBHUI"

MODILEGUISOMEXHUBHUI.Parent = MODILEGUISOMEXHUB

MODILEMAGE.Name = "MODILEMAGE"

MODILEMAGE.Parent = MODILEGUISOMEXHUB

MODILEMAGE.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

MODILEMAGE.BackgroundTransparency = 1.000

MODILEMAGE.BorderSizePixel = 0

MODILEMAGE.Position = UDim2.new(0.234619886, 0, 0.239034846, 0)

MODILEMAGE.Size = UDim2.new(0, 25, 0, 25)

MODILEMAGE.Image = "http://www.roblox.com/asset/?id=7040391851"

wait(1)

local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/kickTh/New-Ui/main/discord%20lib%20(1).txt")()

local win = DiscordLib:Window("SOME X HUB Free-Script")

local serv = win:Server("SOME X HUB", "http://www.roblox.com/asset/?id=7252023075")

local XXX = serv:Channel("Main")

XXX:Toggle("Auto Luck Block ",_G.Luck,function(value)

    _G.Luck = value

end)

spawn(function()

		while wait() do

			if _G.Luck then

				Luckblock()

			end

		end

	end)

		function Luckblock()

	while wait() do

		if _G.Luck then

for i=1, 10 do

        game.ReplicatedStorage.SpawnLuckyBlock:FireServer()

    end

end

end

end

XXX:Toggle("Auto Diamond Block ",_G.Diamond,function(value)

    _G.Diamond = value

end)

spawn(function()

		while wait() do

			if _G.Diamond then

				Diamondblock()

			end

		end

	end)

	

	function Diamondblock()

	while wait() do

		if _G.Diamond then

for i=1, 10 do

        game.ReplicatedStorage.SpawnDiamondBlock:FireServer()

    end

end

end

end

XXX:Toggle("Auto Super Block ",_G.Super,function(value)

    _G.Super = value

end)

spawn(function()

		while wait() do

			if _G.Super then

				Superblock()

			end

		end

	end)

	

	function Superblock()

	while wait() do

		if _G.Super then

for i=1, 10 do

        game.ReplicatedStorage.SpawnSuperBlock:FireServer()

    end

end

end

end

XXX:Toggle("Auto Rainbow Block ",_G.Rainbow,function(value)

    _G.Rainbow = value

end)

spawn(function()

		while wait() do

			if _G.Rainbow then

				Rainbowblock()

			end

		end

	end)

	

	function Rainbowblock()

	while wait() do

		if _G.Rainbow then

for i=1, 10 do

        game.ReplicatedStorage.SpawnRainbowBlock:FireServer()

    end

end

end

end

XXX:Toggle("Auto Galaxy Block ",_G.Galaxy,function(value)

    _G.Galaxy = value

end)

spawn(function()

		while wait() do

			if _G.Galaxy then

				Galaxyblock()

			end

		end

	end)

	

	function Galaxyblock()

	while wait() do

		if _G.Galaxy then

for i=1, 10 do

        game.ReplicatedStorage.SpawnGalaxyBlock:FireServer()

    end

end

end

end

XXX:Toggle("Auto ALL Block ",_G.Allluck,function(value)

    _G.Allluck = value

end)

spawn(function()

		while wait() do

			if _G.Allluck then

				aAllblock()

			end

		end

	end)

	

	function aAllblock()

	while wait() do

		if _G.Allluck then

for i=1, 100 do

        game.ReplicatedStorage.SpawnLuckyBlock:FireServer()

    end

for i=1, 100 do

        game.ReplicatedStorage.SpawnDiamondBlock:FireServer()

    end

for i=1, 100 do

        game.ReplicatedStorage.SpawnSuperBlock:FireServer()

    end

for i=1, 100 do

        game.ReplicatedStorage.SpawnRainbowBlock:FireServer()

    end

for i=1, 100 do

        game.ReplicatedStorage.SpawnGalaxyBlock:FireServer()

    end

end

end

end

	

XXX:Button("Lucky Block",function()

    for i=1, 1 do

        game.ReplicatedStorage.SpawnLuckyBlock:FireServer()

    end

end)

 

XXX:Button("Diamond Block",function()

    for i=1, 1 do

        game.ReplicatedStorage.SpawnDiamondBlock:FireServer()

    end

end)

 

XXX:Button("Super Block",function()

    for i=1, 1 do

        game.ReplicatedStorage.SpawnSuperBlock:FireServer()

    end

end)

 

XXX:Button("Rainbow Block",function()

    for i=1, 1 do 

        game.ReplicatedStorage.SpawnRainbowBlock:FireServer()

    end

end)

 

XXX:Button("Galaxy Block",function()

    for i=1, 1 do 

game:GetService("ReplicatedStorage").SpawnGalaxyBlock:FireServer()

end

end)

	

local XXXT = serv:Channel("Teleport")

XXXT:Label("Teleport")

XXXT:Button("Map Luck Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1041.38464, 194.447006, 90.9088974, -0.0311784502, 2.85457409e-05, -0.999513805, -4.31343979e-05, 1, 2.99051444e-05, 0.999513805, 4.40458243e-05, -0.0311784483)

end)

XXXT:Button("Blue Teleport",function()

			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1256.82996, 193.499908, 206.702667, -0.161815494, -5.69779459e-08, -0.986821055, 7.85692293e-08, 1, -7.06223915e-08, 0.986821055, -8.89615634e-08, -0.161815494)

end)

XXXT:Button("Light blue Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1212.20959, 193.563065, -23.1860218, -0.532320797, -2.16336048e-06, -0.846542716, -6.02430509e-06, 1, 1.23266341e-06, 0.846542716, 5.75600416e-06, -0.532320797)

end)

XXXT:Button("Red Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1155.16931, 193.599792, 262.391235, 0.921236575, 3.95997688e-07, 0.38900277, -5.19419075e-07, 1, 2.12106926e-07, -0.38900277, -3.9745612e-07, 0.921236575)

end)

XXXT:Button("Pink Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-870.817566, 193.581924, 206.454575, 0.706521571, 1.14681634e-05, 0.707691491, -1.86636935e-05, 1, 2.42780857e-06, -0.707691491, -1.49234374e-05, 0.706521571)

end)

XXXT:Button("Purple Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-924.435303, 193.59993, 261.814789, 0.999071896, 1.0758994e-05, -0.0430740714, -1.05433928e-05, 1, 5.23254539e-06, 0.0430740714, -4.77354206e-06, 0.999071896)

end)

XXXT:Button("Orange Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-870.144775, 193.59993, -23.9205303, 0.511242628, 1.76266019e-06, 0.859436452, -5.67409825e-06, 1, 1.32433377e-06, -0.859436452, -5.55358247e-06, 0.511242628)

end)

XXXT:Button("Yellow Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-927.658813, 193.59993, -77.3360443, -0.498395771, -2.08499202e-07, -0.866949618, -1.45483946e-05, 1, 8.12314738e-06, 0.866949618, 1.66612681e-05, -0.498395771)

end)

XXXT:Button("Green Teleport",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1157.79199, 193.599854, -80.760025, -0.772069275, -1.02132244e-05, -0.635538399, -2.94245965e-05, 1, 1.96756046e-05, 0.635538399, 3.38913924e-05, -0.772069275)

end)

local Players = serv:Channel("Player")

	

Players:Toggle("ESP Player",false,function(a)

		ESPPlayer = a

		while ESPPlayer do wait()

			UpdatePlayerChams()

		end

	end)

function isnil(thing)

		return (thing == nil)

	end

	local function round(n)

		return math.floor(tonumber(n) + 0.5)

	end

	Number = math.random(1, 1000000)

	function UpdatePlayerChams()

		for i,v in pairs(game:GetService'Players':GetChildren()) do

			pcall(function()

				if not isnil(v.Character) then

					if ESPPlayer then

						if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then

							local bill = Instance.new('BillboardGui',v.Character.Head)

							bill.Name = 'NameEsp'..Number

							bill.ExtentsOffset = Vector3.new(0, 1, 0)

							bill.Size = UDim2.new(1,200,1,30)

							bill.Adornee = v.Character.Head

							bill.AlwaysOnTop = true

							local name = Instance.new('TextLabel',bill)

							name.Font = "GothamBold"

							name.FontSize = "Size14"

							name.TextWrapped = true

							name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')

							name.Size = UDim2.new(1,0,1,0)

							name.TextYAlignment = 'Top'

							name.BackgroundTransparency = 1

							name.TextStrokeTransparency = 0.5

							if v.Team == game.Players.LocalPlayer.Team then

								name.TextColor3 = Color3.new(255,0,255)

							else

								name.TextColor3 = Color3.new(255,0,0)

							end

						else

							v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')

						end

					else

						if v.Character.Head:FindFirstChild('NameEsp'..Number) then

							v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()

						end

					end

				end

			end)

		end

	end

	PlayerName = {}

	for i,v in pairs(game.Players:GetChildren()) do  

		table.insert(PlayerName ,v.Name)

	end

	SelectedKillPlayer = ""

	local Player = Players:Dropdown("Selected Player",PlayerName,function(plys) --true/false, replaces the current title "Dropdown" with the option that t

		SelectedKillPlayer = plys

		SelectedPly:Refresh("Selected Player : "..SelectedKillPlayer)

	end)

	Players:Button("Refrsh Player",function()

		PlayerName = {}

		Player:Clear()

		for i,v in pairs(game.Players:GetChildren()) do  

			Player:Add(v.Name)

		end

	end)

	

	Players:Button("Teleport Player",function()

		local plr1 = game.Players.LocalPlayer.Character

		local plr2 = game.Players:FindFirstChild(SelectedKillPlayer)

		plr1.HumanoidRootPart.CFrame = plr2.Character.HumanoidRootPart.CFrame

	end)

	Players:Toggle("Spectate Player",false,function(bool)

		Sp = bool

		local plr1 = game.Players.LocalPlayer.Character.Humanoid

		local plr2 = game.Players:FindFirstChild(SelectedKillPlayer)

		repeat wait(.1)

			game.Workspace.Camera.CameraSubject = plr2.Character.Humanoid

		until Sp == false 

		game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid

	end)

	

	local vu = game:GetService("VirtualUser")

game:GetService("Players").LocalPlayer.Idled:connect(function()

   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

   wait(1)

   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

   end)
