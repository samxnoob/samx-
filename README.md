
--/ Important checks 'n waiting for stuff to load or smthing

repeat
	wait()
until game:GetService("Players").LocalPlayer ~= nil

if not game:GetService("Players").LocalPlayer.Character then
	game:GetService("Players").LocalPlayer.CharacterAdded:Wait()
end



--/ Variables & Da Hood Gui Clones Deletion

local LocalPlayer = game:GetService("Players").LocalPlayer
local Character = LocalPlayer.Character
local Workspace = game:GetService("Workspace")
local CoreGui = game:GetService("CoreGui")

local LockedPlayer = nil

for i, v in pairs(game:GetService("CoreGui"):GetChildren()) do
	if v.Name == "ScreenGui" then
		v:Destroy()
	end
end


function Contains(group, text)
	if string.find(group, text) then
		return true;
	else
		return false;
	end
end

local Name = game:GetService('Players').LocalPlayer.Name;
local ID = game:GetService('Players').LocalPlayer.userId;
local Format = (Name..'|'..ID);
local Whitelist = game:HttpGet('https://pastebin.com/kamRXmSH')

if Contains(Whitelist, Name) and Contains(Whitelist, ID) then
	print("Trial Accepted")
	game.StarterGui:SetCore("SendNotification", {
		Title = "SamX";
		Text = "Whitelisted! Enjoy SamX"
	})
else
	LocalPlayer:Kick("GO BUY SAMX")
end


-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local topline = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local Page1Frame = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Goto = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Cash = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local AntiStomp = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local AntiBag = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local LockBtn = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local FlySlow = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local FlyFast = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local UnLockBtn = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local UnBan = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local GodMode = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_14 = Instance.new("UICorner")
local samxlabel = Instance.new("TextLabel")
local Page1Button = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local TpPageButton = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Page3Button = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local Page2Button = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local Page2Frame = Instance.new("Frame")
local UICorner_19 = Instance.new("UICorner")
local AllAnimations = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local AllEmotes = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local Naked = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local ToolReach = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local GodBlock = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local AntiSlow = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local AntiFlash = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local Floatfists = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local GodBullet = Instance.new("TextButton")
local UICorner_28 = Instance.new("UICorner")
local Headless = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local Tornado = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")
local FistReach = Instance.new("TextButton")
local UICorner_31 = Instance.new("UICorner")
local Page3Frame = Instance.new("Frame")
local UICorner_32 = Instance.new("UICorner")
local soon = Instance.new("TextButton")
local UICorner_33 = Instance.new("UICorner")
local soon_2 = Instance.new("TextButton")
local UICorner_34 = Instance.new("UICorner")
local soon_3 = Instance.new("TextButton")
local UICorner_35 = Instance.new("UICorner")
local soon_4 = Instance.new("TextButton")
local UICorner_36 = Instance.new("UICorner")
local soon_5 = Instance.new("TextButton")
local UICorner_37 = Instance.new("UICorner")
local soon_6 = Instance.new("TextButton")
local UICorner_38 = Instance.new("UICorner")
local soon_7 = Instance.new("TextButton")
local UICorner_39 = Instance.new("UICorner")
local soon_8 = Instance.new("TextButton")
local UICorner_40 = Instance.new("UICorner")
local soon_9 = Instance.new("TextButton")
local UICorner_41 = Instance.new("UICorner")
local soon_10 = Instance.new("TextButton")
local UICorner_42 = Instance.new("UICorner")
local P90Farm = Instance.new("TextButton")
local UICorner_43 = Instance.new("UICorner")
local soon_11 = Instance.new("TextButton")
local UICorner_44 = Instance.new("UICorner")
local TpPageButton_2 = Instance.new("Frame")
local UICorner_45 = Instance.new("UICorner")
local GunShop1 = Instance.new("TextButton")
local UICorner_46 = Instance.new("UICorner")
local GunShop2 = Instance.new("TextButton")
local UICorner_47 = Instance.new("UICorner")
local UFO = Instance.new("TextButton")
local UICorner_48 = Instance.new("UICorner")
local Admin = Instance.new("TextButton")
local UICorner_49 = Instance.new("UICorner")
local PhoneShop = Instance.new("TextButton")
local UICorner_50 = Instance.new("UICorner")
local MaskShop = Instance.new("TextButton")
local UICorner_51 = Instance.new("UICorner")
local Prison = Instance.new("TextButton")
local UICorner_52 = Instance.new("UICorner")
local Bank = Instance.new("TextButton")
local UICorner_53 = Instance.new("UICorner")
local line = Instance.new("Frame")
local UICorner_54 = Instance.new("UICorner")
local function ShrinkName()
	TextBox.FocusLost:connect(function()
		for i,v in pairs(game.Players:GetChildren()) do
			if (string.sub(string.lower(v.Name),1,string.len(TextBox.Text))) == string.lower(TextBox.Text) then
				TextBox.Text = v.Name
			end
		end
	end)
end

ShrinkName()
function findPlayer(name)
	name = name:lower()
	if name == 'me' then
		return game:GetService'Players'.LocalPlayer
	end
	for i,v in pairs(game:GetService'Players':GetPlayers()) do
		if v.Name:lower():find(name) == 1 then
			return v
		end
	end
end

--Properties:

ScreenGui.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
MainFrame.Position = UDim2.new(0.4760409, 0, 0.317206174, 0)
MainFrame.Size = UDim2.new(0, 456, 0, 232)
MainFrame.Active = true
MainFrame.Draggable = true

topline.Name = "top line"
topline.Parent = MainFrame
topline.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
topline.BorderColor3 = Color3.fromRGB(0, 170, 0)
topline.Position = UDim2.new(0, 0, -0.0172413792, 0)
topline.Size = UDim2.new(0, 456, 0, 19)

UICorner.Parent = topline

UICorner_2.Parent = MainFrame

Page1Frame.Name = "Page1Frame"
Page1Frame.Parent = MainFrame
Page1Frame.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
Page1Frame.BorderColor3 = Color3.fromRGB(98, 98, 98)
Page1Frame.Position = UDim2.new(0.0350877196, 0, 0.232758611, 0)
Page1Frame.Size = UDim2.new(0, 424, 0, 154)

UICorner_3.Parent = Page1Frame

Goto.Name = "Goto"
Goto.Parent = Page1Frame
Goto.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Goto.Position = UDim2.new(0.257075489, 0, 0.688311696, 0)
Goto.Size = UDim2.new(0, 96, 0, 34)
Goto.Font = Enum.Font.SourceSans
Goto.Text = "Goto"
Goto.TextColor3 = Color3.fromRGB(0, 193, 0)
Goto.TextSize = 20.000
Goto.MouseButton1Click:connect(function()
	local TargetPlr = TextBox.Text;
	local A_1 = "Teleporting To " .. TargetPlr .. " By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
	wait(.30)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[TargetPlr].Character.HumanoidRootPart.CFrame
end)

UICorner_4.Parent = Goto

Cash.Name = "Cash"
Cash.Parent = Page1Frame
Cash.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Cash.Position = UDim2.new(0.502358615, 0, 0.688311696, 0)
Cash.Size = UDim2.new(0, 98, 0, 34)
Cash.Font = Enum.Font.SourceSans
Cash.Text = "See Cash"
Cash.TextColor3 = Color3.fromRGB(0, 193, 0)
Cash.TextSize = 20.000
Cash.MouseButton1Click:connect(function()
	local TargetPlr = TextBox.Text;
	local A_1 = "SamX: " .. TargetPlr .. " Has $" .. game.Players[TargetPlr].DataFolder.Currency.Value .. "." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2)
end)

UICorner_5.Parent = Cash

AntiStomp.Name = "AntiStomp"
AntiStomp.Parent = Page1Frame
AntiStomp.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
AntiStomp.Position = UDim2.new(0.0212264154, 0, 0.688311696, 0)
AntiStomp.Size = UDim2.new(0, 91, 0, 34)
AntiStomp.Font = Enum.Font.SourceSans
AntiStomp.Text = "AntiStomp"
AntiStomp.TextColor3 = Color3.fromRGB(0, 193, 0)
AntiStomp.TextSize = 20.000
AntiStomp.MouseButton1Down:connect(function()
	wait(0) local A_1 = "AntiStomp Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	pcall(function() if tostring(game.PlaceId) == "2788229376" then local corepackages = game:GetService"CorePackages" local localplayer = game:GetService"Players".LocalPlayer local run = game:GetService"RunService" run:BindToRenderStep("rrrrrrrrrrr",2000,function() pcall(function() if localplayer.Character.Humanoid.Health <= 30 then localplayer.Character.Humanoid:UnequipTools() localplayer.Character.Humanoid:Destroy() workspace.CurrentCamera.CameraSubject = localplayer.Character wait() local prt = Instance.new("Model", corepackages); Instance.new("Part", prt).Name="Torso"; Instance.new("Part", prt).Name="Head"; Instance.new("Humanoid", prt).Name="Humanoid"; localplayer.Character=prt end end) pcall(function() if localplayer.Character.Humanoid.FloorMaterial == "Plastic" then ReplicatedStorage:FireServer("Stomp") end end) end) loadstring(game:HttpGet("https://pastebin.com/raw/MQ3wc7Zq", true))() end end)
end)


UICorner_6.Parent = AntiStomp

AntiBag.Name = "AntiBag"
AntiBag.Parent = Page1Frame
AntiBag.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
AntiBag.Position = UDim2.new(0.75, 0, 0.688311696, 0)
AntiBag.Size = UDim2.new(0, 98, 0, 34)
AntiBag.Font = Enum.Font.SourceSans
AntiBag.Text = "AntiBag"
AntiBag.TextColor3 = Color3.fromRGB(0, 193, 0)
AntiBag.TextSize = 20.000
AntiBag.MouseButton1Down:connect(function()

	wait(0) local A_1 = "AntiBag Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	local LocalPlayer = game:GetService("Players").LocalPlayer
	local char = LocalPlayer.Character
	char.ChildAdded:Connect(function(sock)
		if sock:IsA("MeshPart") then do
				wait(0.1)
				sock:Destroy()
			end
		end
	end)										
end)

UICorner_7.Parent = AntiBag

LockBtn.Name = "LockBtn"
LockBtn.Parent = Page1Frame
LockBtn.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
LockBtn.Position = UDim2.new(0.257075548, 0, 0.38961041, 0)
LockBtn.Size = UDim2.new(0, 98, 0, 34)
LockBtn.Font = Enum.Font.SourceSans
LockBtn.Text = "Lock"
LockBtn.TextColor3 = Color3.fromRGB(0, 193, 0)
LockBtn.TextSize = 20.000
LockBtn.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Target Locked By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	game:GetService("StarterGui"):SetCore("SendNotification",{
		Title = "Sam X";
		Text = "Lock/Unlock Made by i am a corpse#6924";
	})
end)

UICorner_8.Parent = LockBtn

FlySlow.Name = "Fly Slow"
FlySlow.Parent = Page1Frame
FlySlow.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
FlySlow.Position = UDim2.new(0.0212264359, 0, 0.38961041, 0)
FlySlow.Size = UDim2.new(0, 91, 0, 34)
FlySlow.Font = Enum.Font.SourceSans
FlySlow.Text = "Fly(x)Slow"
FlySlow.TextColor3 = Color3.fromRGB(0, 193, 0)
FlySlow.TextSize = 20.000
FlySlow.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	local mouse = plr:GetMouse()

	localplayer = plr

	if workspace:FindFirstChild("Core") then
		workspace.Core:Destroy()
	end

	local Core = Instance.new("Part")
	Core.Name = "Core"
	Core.Size = Vector3.new(0.05, 0.05, 0.05)

	spawn(function()
		Core.Parent = workspace
		local Weld = Instance.new("Weld", Core)
		Weld.Part0 = Core
		Weld.Part1 = localplayer.Character.LowerTorso
		Weld.C0 = CFrame.new(0, 0, 0)
	end)

	workspace:WaitForChild("Core")

	local torso = workspace.Core
	flying = true
	local speed=10
	local keys={a=false,d=false,w=false,s=false}
	local e1
	local e2
	local function start()
		local pos = Instance.new("BodyPosition",torso)
		local gyro = Instance.new("BodyGyro",torso)
		pos.Name="EPIXPOS"
		pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
		pos.position = torso.Position
		gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
		gyro.cframe = torso.CFrame
		repeat
			wait()
			localplayer.Character.Humanoid.PlatformStand=true
			local new=gyro.cframe - gyro.cframe.p + pos.position
			if not keys.w and not keys.s and not keys.a and not keys.d then
				speed=5
			end
			if keys.w then
				new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
				speed=speed+0
			end
			if keys.s then
				new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
				speed=speed+0
			end
			if keys.d then
				new = new * CFrame.new(speed,0,0)
				speed=speed+0
			end
			if keys.a then
				new = new * CFrame.new(-speed,0,0)
				speed=speed+0
			end
			if speed>10 then
				speed=5
			end
			pos.position=new.p
			if keys.w then
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*0),0,0)
			elseif keys.s then
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*0),0,0)
			else
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame
			end
		until flying == false
		if gyro then gyro:Destroy() end
		if pos then pos:Destroy() end
		flying=false
		localplayer.Character.Humanoid.PlatformStand=false
		speed=10
	end
	e1=mouse.KeyDown:connect(function(key)
		if not torso or not torso.Parent then flying=false e1:disconnect() e2:disconnect() return end
		if key=="w" then
			keys.w=true
		elseif key=="s" then
			keys.s=true
		elseif key=="a" then
			keys.a=true
		elseif key=="d" then
			keys.d=true
		elseif key=="x" then
			if flying==true then
				flying=false
			else
				flying=true
				start()
			end
		end
	end)
	e2=mouse.KeyUp:connect(function(key)
		if key=="w" then
			keys.w=false
		elseif key=="s" then
			keys.s=false
		elseif key=="a" then
			keys.a=false
		elseif key=="d" then
			keys.d=false
		end
	end)
	start()
end)

UICorner_9.Parent = FlySlow

FlyFast.Name = "Fly Fast"
FlyFast.Parent = Page1Frame
FlyFast.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
FlyFast.Position = UDim2.new(0.0212264359, 0, 0.0584415533, 0)
FlyFast.Size = UDim2.new(0, 91, 0, 34)
FlyFast.Font = Enum.Font.SourceSans
FlyFast.Text = "Fly(x)Fast"
FlyFast.TextColor3 = Color3.fromRGB(0, 193, 0)
FlyFast.TextSize = 20.000
FlyFast.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Fly Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	local plr = game.Players.LocalPlayer
	local mouse = plr:GetMouse()

	localplayer = plr

	if workspace:FindFirstChild("Core") then
		workspace.Core:Destroy()
	end

	local Core = Instance.new("Part")
	Core.Name = "Core"
	Core.Size = Vector3.new(0.05, 0.05, 0.05)

	spawn(function()
		Core.Parent = workspace
		local Weld = Instance.new("Weld", Core)
		Weld.Part0 = Core
		Weld.Part1 = localplayer.Character.LowerTorso
		Weld.C0 = CFrame.new(0, 0, 0)
	end)

	workspace:WaitForChild("Core")

	local torso = workspace.Core
	flying = true
	local speed=40
	local keys={a=false,d=false,w=false,s=false}
	local e1
	local e2
	local function start()
		local pos = Instance.new("BodyPosition",torso)
		local gyro = Instance.new("BodyGyro",torso)
		pos.Name="EPIXPOS"
		pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
		pos.position = torso.Position
		gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
		gyro.cframe = torso.CFrame
		repeat
			wait()
			localplayer.Character.Humanoid.PlatformStand=true
			local new=gyro.cframe - gyro.cframe.p + pos.position
			if not keys.w and not keys.s and not keys.a and not keys.d then
				speed=40
			end
			if keys.w then
				new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
				speed=speed+0
			end
			if keys.s then
				new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
				speed=speed+0
			end
			if keys.d then
				new = new * CFrame.new(speed,0,0)
				speed=speed+0
			end
			if keys.a then
				new = new * CFrame.new(-speed,0,0)
				speed=speed+0
			end
			if speed>10 then
				speed=40
			end
			pos.position=new.p
			if keys.w then
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*0),0,0)
			elseif keys.s then
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*0),0,0)
			else
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame
			end
		until flying == false
		if gyro then gyro:Destroy() end
		if pos then pos:Destroy() end
		flying=false
		localplayer.Character.Humanoid.PlatformStand=false
		speed=40
	end
	e1=mouse.KeyDown:connect(function(key)
		if not torso or not torso.Parent then flying=false e1:disconnect() e2:disconnect() return end
		if key=="w" then
			keys.w=true
		elseif key=="s" then
			keys.s=true
		elseif key=="a" then
			keys.a=true
		elseif key=="d" then
			keys.d=true
		elseif key=="x" then
			if flying==true then
				flying=false
			else
				flying=true
				start()
			end
		end
	end)
	e2=mouse.KeyUp:connect(function(key)
		if key=="w" then
			keys.w=false
		elseif key=="s" then
			keys.s=false
		elseif key=="a" then
			keys.a=false
		elseif key=="d" then
			keys.d=false
		end
	end)
	start() 																		
end)

UICorner_10.Parent = FlyFast

UnLockBtn.Name = "UnLockBtn"
UnLockBtn.Parent = Page1Frame
UnLockBtn.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
UnLockBtn.Position = UDim2.new(0.504717052, 0, 0.38961041, 0)
UnLockBtn.Size = UDim2.new(0, 98, 0, 34)
UnLockBtn.Font = Enum.Font.SourceSans
UnLockBtn.Text = "Unlock"
UnLockBtn.TextColor3 = Color3.fromRGB(0, 193, 0)
UnLockBtn.TextSize = 20.000
UnLockBtn.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Target Unlocked By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
end)
UICorner_11.Parent = UnLockBtn

UnBan.Name = "UnBan"
UnBan.Parent = Page1Frame
UnBan.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
UnBan.Position = UDim2.new(0.75000006, 0, 0.38961041, 0)
UnBan.Size = UDim2.new(0, 98, 0, 34)
UnBan.Font = Enum.Font.SourceSans
UnBan.Text = "UnBan"
UnBan.TextColor3 = Color3.fromRGB(0, 193, 0)
UnBan.TextSize = 20.000
UnBan.MouseButton1Down:connect(function()

	wait(0) local A_1 = "UnBan Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

	if game.PlaceId == 2788229376 then -- // Detecting if the game is Da Hood

		if not game:IsLoaded() then
			game.Loaded:Wait()
			print("Game loaded!")
		end

		-- // Variables

		local Players = game:GetService("Players")
		local LocalPlayer = Players.LocalPlayer

		-- // Doing the UnBan

		LocalPlayer.CharacterAdded:Connect(function(char)
			local fol = Instance.new("Folder")
			fol.Name = "FULLY_LOADED_CHAR"
			fol.Parent = char
		end)

		spawn(function()
			while wait() do
				for _,obj in pairs(LocalPlayer.Character:GetDescendants()) do
					if obj.Name == "SpecialParts" then
						obj:Destroy()
					end
				end
			end
		end)

	else
		return
	end
end)

UICorner_12.Parent = UnBan

GodMode.Name = "GodMode"
GodMode.Parent = Page1Frame
GodMode.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
GodMode.Position = UDim2.new(0.75000006, 0, 0.0584415793, 0)
GodMode.Size = UDim2.new(0, 98, 0, 34)
GodMode.Font = Enum.Font.SourceSans
GodMode.Text = "GodMode"
GodMode.TextColor3 = Color3.fromRGB(0, 193, 0)
GodMode.TextSize = 20.000
GodMode.MouseButton1Down:connect(function()
	wait(0) local A_1 = "GodMode Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	local name = game.Players.LocalPlayer.Name
	game.Players.LocalPlayer.Character.Humanoid.Health = 0
	game.Players.LocalPlayer.Character:ClearAllChildren()
	local lol =    game.Workspace:WaitForChild(name)
	local money = Instance.new("Folder",game.Players.LocalPlayer.Character);money.Name = "FULLY_LOADED_CHAR"
	lol.Parent = game.Workspace.Players
	game.Players.LocalPlayer.Character:WaitForChild("BodyEffects")
	game.Players.LocalPlayer.Character.BodyEffects.BreakingParts:Destroy()
end)

UICorner_13.Parent = GodMode

TextBox.Parent = Page1Frame
TextBox.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
TextBox.BorderColor3 = Color3.fromRGB(0, 255, 0)
TextBox.Position = UDim2.new(0.257075459, 0, 0.058441557, 0)
TextBox.Size = UDim2.new(0, 199, 0, 34)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 193, 0)
TextBox.TextSize = 20.000

UICorner_14.Parent = TextBox

samxlabel.Name = "samx label"
samxlabel.Parent = MainFrame
samxlabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
samxlabel.BackgroundTransparency = 1.000
samxlabel.Position = UDim2.new(0.0153508773, 0, 0.081896551, 0)
samxlabel.Size = UDim2.new(0, 200, 0, 35)
samxlabel.Font = Enum.Font.SourceSansBold
samxlabel.Text = "SamX Premium"
samxlabel.TextColor3 = Color3.fromRGB(0, 193, 0)
samxlabel.TextSize = 30.000
samxlabel.TextStrokeColor3 = Color3.fromRGB(0, 170, 0)

Page1Button.Name = "Page1Button"
Page1Button.Parent = MainFrame
Page1Button.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
Page1Button.BorderColor3 = Color3.fromRGB(98, 98, 98)
Page1Button.Position = UDim2.new(0.0701754391, 0, 0.870689631, 0)
Page1Button.Size = UDim2.new(0, 76, 0, 23)
Page1Button.Font = Enum.Font.SourceSans
Page1Button.Text = "Page1"
Page1Button.TextColor3 = Color3.fromRGB(0, 193, 0)
Page1Button.TextSize = 20.000
Page1Button.MouseButton1Down:connect(function()
	Page1Frame.Visible = true
	Page2Frame.Visible = false
	Page3Frame.Visible = false
	TpPageButton_2.Visible = false
end)

UICorner_15.Parent = Page1Button

TpPageButton.Name = "TpPageButton"
TpPageButton.Parent = MainFrame
TpPageButton.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
TpPageButton.BorderColor3 = Color3.fromRGB(98, 98, 98)
TpPageButton.Position = UDim2.new(0.75, 0, 0.866379321, 0)
TpPageButton.Size = UDim2.new(0, 76, 0, 23)
TpPageButton.Font = Enum.Font.SourceSans
TpPageButton.Text = "TpPage"
TpPageButton.TextColor3 = Color3.fromRGB(0, 193, 0)
TpPageButton.TextSize = 20.000
TpPageButton.MouseButton1Down:connect(function()
	Page1Frame.Visible = false
	Page2Frame.Visible = false
	Page3Frame.Visible = false
	TpPageButton_2.Visible = true
end)


UICorner_16.Parent = TpPageButton

Page3Button.Name = "Page3Button"
Page3Button.Parent = MainFrame
Page3Button.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
Page3Button.BorderColor3 = Color3.fromRGB(98, 98, 98)
Page3Button.Position = UDim2.new(0.526315808, 0, 0.866379321, 0)
Page3Button.Size = UDim2.new(0, 76, 0, 23)
Page3Button.Font = Enum.Font.SourceSans
Page3Button.Text = "Page3"
Page3Button.TextColor3 = Color3.fromRGB(0, 193, 0)
Page3Button.TextSize = 20.000
Page3Button.MouseButton1Down:connect(function()
	Page1Frame.Visible = false
	Page2Frame.Visible = false
	Page3Frame.Visible = true
	TpPageButton_2.Visible = false
end)


UICorner_17.Parent = Page3Button

Page2Button.Name = "Page2Button"
Page2Button.Parent = MainFrame
Page2Button.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
Page2Button.BorderColor3 = Color3.fromRGB(98, 98, 98)
Page2Button.Position = UDim2.new(0.298245609, 0, 0.87068969, 0)
Page2Button.Size = UDim2.new(0, 76, 0, 23)
Page2Button.Font = Enum.Font.SourceSans
Page2Button.Text = "Page2"
Page2Button.TextColor3 = Color3.fromRGB(0, 193, 0)
Page2Button.TextSize = 20.000
Page2Button.MouseButton1Down:connect(function()
	Page1Frame.Visible = false
	Page2Frame.Visible = true
	Page3Frame.Visible = false
	TpPageButton_2.Visible = false
end)


UICorner_18.Parent = Page2Button

Page2Frame.Name = "Page2Frame"
Page2Frame.Parent = MainFrame
Page2Frame.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
Page2Frame.BorderColor3 = Color3.fromRGB(98, 98, 98)
Page2Frame.Position = UDim2.new(0.0350877084, 0, 0.206896573, 0)
Page2Frame.Size = UDim2.new(0, 424, 0, 154)
Page2Frame.Visible = false

UICorner_19.Parent = Page2Frame

AllAnimations.Name = "AllAnimations"
AllAnimations.Parent = Page2Frame
AllAnimations.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
AllAnimations.Position = UDim2.new(0.257075489, 0, 0.688311696, 0)
AllAnimations.Size = UDim2.new(0, 96, 0, 34)
AllAnimations.Font = Enum.Font.SourceSans
AllAnimations.Text = "All Anim"
AllAnimations.TextColor3 = Color3.fromRGB(0, 193, 0)
AllAnimations.TextSize = 20.000
AllAnimations.MouseButton1Down:connect(function()
	local AnimationChanger = Instance.new("ScreenGui")
	local Main = Instance.new("Frame")
	local TopBar = Instance.new("Frame")
	local Close = Instance.new("TextButton")
	local TextLabel = Instance.new("TextLabel")
	local TextLabel_2 = Instance.new("TextLabel")
	local NormalTab = Instance.new("Frame")
	local A_Astronaut = Instance.new("TextButton")
	local A_Bubbly = Instance.new("TextButton")
	local A_Cartoony = Instance.new("TextButton")
	local A_Elder = Instance.new("TextButton")
	local A_Knight = Instance.new("TextButton")
	local A_Levitation = Instance.new("TextButton")
	local A_Mage = Instance.new("TextButton")
	local A_Ninja = Instance.new("TextButton")
	local A_Pirate = Instance.new("TextButton")
	local A_Robot = Instance.new("TextButton")
	local A_Stylish = Instance.new("TextButton")
	local A_SuperHero = Instance.new("TextButton")
	local A_Toy = Instance.new("TextButton")
	local A_Vampire = Instance.new("TextButton")
	local A_Werewolf = Instance.new("TextButton")
	local A_Zombie = Instance.new("TextButton")
	local Category = Instance.new("TextLabel")
	local SpecialTab = Instance.new("Frame")
	local A_Patrol = Instance.new("TextButton")
	local A_Confident = Instance.new("TextButton")
	local A_Popstar = Instance.new("TextButton")
	local A_Cowboy = Instance.new("TextButton")
	local A_Ghost = Instance.new("TextButton")
	local A_Sneaky = Instance.new("TextButton")
	local A_Princess = Instance.new("TextButton")
	local Category_2 = Instance.new("TextLabel")
	local OtherTab = Instance.new("Frame")
	local Category_3 = Instance.new("TextLabel")
	local A_None = Instance.new("TextButton")
	local A_Anthro = Instance.new("TextButton")
	local Animate = game.Players.LocalPlayer.Character.Animate

	AnimationChanger.Name = "AnimationChanger"
	AnimationChanger.Parent = game:WaitForChild("CoreGui")
	AnimationChanger.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	Main.Name = "Main"
	Main.Parent = AnimationChanger
	Main.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
	Main.BorderSizePixel = 0
	Main.Position = UDim2.new(0.421999991, 0, -1, 0)
	Main.Size = UDim2.new(0, 300, 0, 250)
	Main.Active = true
	Main.Draggable = true

	TopBar.Name = "TopBar"
	TopBar.Parent = Main
	TopBar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	TopBar.BorderSizePixel = 0
	TopBar.Size = UDim2.new(0, 300, 0, 30)

	Close.Name = "Close"
	Close.Parent = TopBar
	Close.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	Close.BorderSizePixel = 0
	Close.Position = UDim2.new(0.899999976, 0, 0, 0)
	Close.Size = UDim2.new(0, 30, 0, 30)
	Close.Font = Enum.Font.SciFi
	Close.Text = "x"
	Close.TextColor3 = Color3.new(1, 0, 0.0156863)
	Close.TextSize = 20
	Close.MouseButton1Click:Connect(function()
		wait(0.3)
		Main:TweenPosition(UDim2.new(0.421999991, 0, -1.28400004, 0))
		wait(3)
		AnimationChanger:Destroy()
	end)

	TextLabel.Parent = TopBar
	TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel.BackgroundTransparency = 1
	TextLabel.BorderSizePixel = 0
	TextLabel.Position = UDim2.new(0, 0, 0.600000024, 0)
	TextLabel.Size = UDim2.new(0, 270, 0, 10)
	TextLabel.Font = Enum.Font.SourceSans
	TextLabel.Text = "Made by Nyser#4623"
	TextLabel.TextColor3 = Color3.new(1, 1, 1)
	TextLabel.TextSize = 15

	TextLabel_2.Parent = TopBar
	TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel_2.BackgroundTransparency = 1
	TextLabel_2.BorderSizePixel = 0
	TextLabel_2.Position = UDim2.new(0, 0, -0.0266667679, 0)
	TextLabel_2.Size = UDim2.new(0, 270, 0, 20)
	TextLabel_2.Font = Enum.Font.SourceSans
	TextLabel_2.Text = "Animation Changer"
	TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
	TextLabel_2.TextSize = 20

	NormalTab.Name = "NormalTab"
	NormalTab.Parent = Main
	NormalTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
	NormalTab.BackgroundTransparency = 1
	NormalTab.BorderSizePixel = 0
	NormalTab.Position = UDim2.new(0.5, 0, 0.119999997, 0)
	NormalTab.Size = UDim2.new(0, 150, 0, 500)

	A_Astronaut.Name = "A_Astronaut"
	A_Astronaut.Parent = NormalTab
	A_Astronaut.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Astronaut.BorderSizePixel = 0
	A_Astronaut.Position = UDim2.new(0, 0, 0.815764725, 0)
	A_Astronaut.Size = UDim2.new(0, 150, 0, 30)
	A_Astronaut.Font = Enum.Font.SciFi
	A_Astronaut.Text = "Astronaut"
	A_Astronaut.TextColor3 = Color3.new(1, 1, 1)
	A_Astronaut.TextSize = 20
	A_Astronaut.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Bubbly.Name = "A_Bubbly"
	A_Bubbly.Parent = NormalTab
	A_Bubbly.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Bubbly.BorderSizePixel = 0
	A_Bubbly.Position = UDim2.new(0, 0, 0.349019617, 0)
	A_Bubbly.Size = UDim2.new(0, 150, 0, 30)
	A_Bubbly.Font = Enum.Font.SciFi
	A_Bubbly.Text = "Bubbly"
	A_Bubbly.TextColor3 = Color3.new(1, 1, 1)
	A_Bubbly.TextSize = 20
	A_Bubbly.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
		Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
		Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Cartoony.Name = "A_Cartoony"
	A_Cartoony.Parent = NormalTab
	A_Cartoony.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Cartoony.BorderSizePixel = 0
	A_Cartoony.Position = UDim2.new(0, 0, 0.407272667, 0)
	A_Cartoony.Size = UDim2.new(0, 150, 0, 30)
	A_Cartoony.Font = Enum.Font.SciFi
	A_Cartoony.Text = "Cartoony"
	A_Cartoony.TextColor3 = Color3.new(1, 1, 1)
	A_Cartoony.TextSize = 20
	A_Cartoony.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Elder.Name = "A_Elder"
	A_Elder.Parent = NormalTab
	A_Elder.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Elder.BorderSizePixel = 0
	A_Elder.Position = UDim2.new(6.51925802e-09, 0, 0.636310041, 0)
	A_Elder.Size = UDim2.new(0, 150, 0, 30)
	A_Elder.Font = Enum.Font.SciFi
	A_Elder.Text = "Elder"
	A_Elder.TextColor3 = Color3.new(1, 1, 1)
	A_Elder.TextSize = 20
	A_Elder.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=845397899"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Knight.Name = "A_Knight"
	A_Knight.Parent = NormalTab
	A_Knight.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Knight.BorderSizePixel = 0
	A_Knight.Position = UDim2.new(0, 0, 0.52352941, 0)
	A_Knight.Size = UDim2.new(0, 150, 0, 30)
	A_Knight.Font = Enum.Font.SciFi
	A_Knight.Text = "Knight"
	A_Knight.TextColor3 = Color3.new(1, 1, 1)
	A_Knight.TextSize = 20
	A_Knight.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=657595757"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=657568135"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=657552124"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=657564596"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=658409194"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=658360781"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=657600338"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Levitation.Name = "A_Levitation"
	A_Levitation.Parent = NormalTab
	A_Levitation.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Levitation.BorderSizePixel = 0
	A_Levitation.Position = UDim2.new(0, 0, 0.115472436, 0)
	A_Levitation.Size = UDim2.new(0, 150, 0, 30)
	A_Levitation.Font = Enum.Font.SciFi
	A_Levitation.Text = "Levitation"
	A_Levitation.TextColor3 = Color3.new(1, 1, 1)
	A_Levitation.TextSize = 20
	A_Levitation.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Mage.Name = "A_Mage"
	A_Mage.Parent = NormalTab
	A_Mage.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Mage.BorderSizePixel = 0
	A_Mage.Position = UDim2.new(0, 0, 0.696203232, 0)
	A_Mage.Size = UDim2.new(0, 150, 0, 30)
	A_Mage.Font = Enum.Font.SciFi
	A_Mage.Text = "Mage"
	A_Mage.TextColor3 = Color3.new(1, 1, 1)
	A_Mage.TextSize = 20
	A_Mage.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Ninja.Name = "A_Ninja"
	A_Ninja.Parent = NormalTab
	A_Ninja.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Ninja.BorderSizePixel = 0
	A_Ninja.Position = UDim2.new(0, 0, 0.0597896464, 0)
	A_Ninja.Size = UDim2.new(0, 150, 0, 30)
	A_Ninja.Font = Enum.Font.SciFi
	A_Ninja.Text = "Ninja"
	A_Ninja.TextColor3 = Color3.new(1, 1, 1)
	A_Ninja.TextSize = 20
	A_Ninja.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Pirate.Name = "A_Pirate"
	A_Pirate.Parent = NormalTab
	A_Pirate.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Pirate.BorderSizePixel = 0
	A_Pirate.Position = UDim2.new(-0.000333309174, 0, 0.874588311, 0)
	A_Pirate.Size = UDim2.new(0, 150, 0, 30)
	A_Pirate.Font = Enum.Font.SciFi
	A_Pirate.Text = "Pirate"
	A_Pirate.TextColor3 = Color3.new(1, 1, 1)
	A_Pirate.TextSize = 20
	A_Pirate.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Robot.Name = "A_Robot"
	A_Robot.Parent = NormalTab
	A_Robot.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Robot.BorderSizePixel = 0
	A_Robot.Position = UDim2.new(0, 0, 0.291479498, 0)
	A_Robot.Size = UDim2.new(0, 150, 0, 30)
	A_Robot.Font = Enum.Font.SciFi
	A_Robot.Text = "Robot"
	A_Robot.TextColor3 = Color3.new(1, 1, 1)
	A_Robot.TextSize = 20
	A_Robot.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Stylish.Name = "A_Stylish"
	A_Stylish.Parent = NormalTab
	A_Stylish.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Stylish.BorderSizePixel = 0
	A_Stylish.Position = UDim2.new(0, 0, 0.232816339, 0)
	A_Stylish.Size = UDim2.new(0, 150, 0, 30)
	A_Stylish.Font = Enum.Font.SciFi
	A_Stylish.Text = "Stylish"
	A_Stylish.TextColor3 = Color3.new(1, 1, 1)
	A_Stylish.TextSize = 20
	A_Stylish.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_SuperHero.Name = "A_SuperHero"
	A_SuperHero.Parent = NormalTab
	A_SuperHero.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_SuperHero.BorderSizePixel = 0
	A_SuperHero.Position = UDim2.new(0, 0, 0.464919746, 0)
	A_SuperHero.Size = UDim2.new(0, 150, 0, 30)
	A_SuperHero.Font = Enum.Font.SciFi
	A_SuperHero.Text = "SuperHero"
	A_SuperHero.TextColor3 = Color3.new(1, 1, 1)
	A_SuperHero.TextSize = 20
	A_SuperHero.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Toy.Name = "A_Toy"
	A_Toy.Parent = NormalTab
	A_Toy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Toy.BorderSizePixel = 0
	A_Toy.Position = UDim2.new(6.51925802e-09, 0, 0.756028414, 0)
	A_Toy.Size = UDim2.new(0, 150, 0, 30)
	A_Toy.Font = Enum.Font.SciFi
	A_Toy.Text = "Toy"
	A_Toy.TextColor3 = Color3.new(1, 1, 1)
	A_Toy.TextSize = 20
	A_Toy.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Vampire.Name = "A_Vampire"
	A_Vampire.Parent = NormalTab
	A_Vampire.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Vampire.BorderSizePixel = 0
	A_Vampire.Position = UDim2.new(0, 0, 0.934021354, 0)
	A_Vampire.Size = UDim2.new(0, 150, 0, 30)
	A_Vampire.Font = Enum.Font.SciFi
	A_Vampire.Text = "Vampire"
	A_Vampire.TextColor3 = Color3.new(1, 1, 1)
	A_Vampire.TextSize = 20
	A_Vampire.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Werewolf.Name = "A_Werewolf"
	A_Werewolf.Parent = NormalTab
	A_Werewolf.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Werewolf.BorderSizePixel = 0
	A_Werewolf.Position = UDim2.new(-0.000333368778, 0, 0.174509808, 0)
	A_Werewolf.Size = UDim2.new(0, 150, 0, 30)
	A_Werewolf.Font = Enum.Font.SciFi
	A_Werewolf.Text = "Werewolf"
	A_Werewolf.TextColor3 = Color3.new(1, 1, 1)
	A_Werewolf.TextSize = 20
	A_Werewolf.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Zombie.Name = "A_Zombie"
	A_Zombie.Parent = NormalTab
	A_Zombie.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Zombie.BorderSizePixel = 0
	A_Zombie.Position = UDim2.new(-1.1920929e-07, 0, 0.582352936, 0)
	A_Zombie.Size = UDim2.new(0, 150, 0, 30)
	A_Zombie.Font = Enum.Font.SciFi
	A_Zombie.Text = "Zombie"
	A_Zombie.TextColor3 = Color3.new(1, 1, 1)
	A_Zombie.TextSize = 20
	A_Zombie.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Category.Name = "Category"
	Category.Parent = NormalTab
	Category.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
	Category.BorderSizePixel = 0
	Category.Size = UDim2.new(0, 150, 0, 30)
	Category.Text = "Normal"
	Category.TextColor3 = Color3.new(0, 0.835294, 1)
	Category.TextSize = 14

	SpecialTab.Name = "SpecialTab"
	SpecialTab.Parent = Main
	SpecialTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
	SpecialTab.BackgroundTransparency = 1
	SpecialTab.BorderSizePixel = 0
	SpecialTab.Position = UDim2.new(0, 0, 0.119999997, 0)
	SpecialTab.Size = UDim2.new(0, 150, 0, 230)

	A_Patrol.Name = "A_Patrol"
	A_Patrol.Parent = SpecialTab
	A_Patrol.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Patrol.BorderSizePixel = 0
	A_Patrol.Position = UDim2.new(0, 0, 0.259960413, 0)
	A_Patrol.Size = UDim2.new(0, 150, 0, 30)
	A_Patrol.Font = Enum.Font.SciFi
	A_Patrol.Text = "Patrol"
	A_Patrol.TextColor3 = Color3.new(1, 1, 1)
	A_Patrol.TextSize = 20
	A_Patrol.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Confident.Name = "A_Confident"
	A_Confident.Parent = SpecialTab
	A_Confident.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Confident.BorderSizePixel = 0
	A_Confident.Position = UDim2.new(0, 0, 0.389248967, 0)
	A_Confident.Size = UDim2.new(0, 150, 0, 30)
	A_Confident.Font = Enum.Font.SciFi
	A_Confident.Text = "Confident"
	A_Confident.TextColor3 = Color3.new(1, 1, 1)
	A_Confident.TextSize = 20
	A_Confident.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Popstar.Name = "A_Popstar"
	A_Popstar.Parent = SpecialTab
	A_Popstar.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Popstar.BorderSizePixel = 0
	A_Popstar.Position = UDim2.new(0, 0, 0.130671918, 0)
	A_Popstar.Size = UDim2.new(0, 150, 0, 30)
	A_Popstar.Font = Enum.Font.SciFi
	A_Popstar.Text = "Popstar"
	A_Popstar.TextColor3 = Color3.new(1, 1, 1)
	A_Popstar.TextSize = 20
	A_Popstar.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1212900985"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980338"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1212980348"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1212954642"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1213044953"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1212900995"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Cowboy.Name = "A_Cowboy"
	A_Cowboy.Parent = SpecialTab
	A_Cowboy.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Cowboy.BorderSizePixel = 0
	A_Cowboy.Position = UDim2.new(0, 0, 0.772964239, 0)
	A_Cowboy.Size = UDim2.new(0, 150, 0, 30)
	A_Cowboy.Font = Enum.Font.SciFi
	A_Cowboy.Text = "Cowboy"
	A_Cowboy.TextColor3 = Color3.new(1, 1, 1)
	A_Cowboy.TextSize = 20
	A_Cowboy.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1014390418"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1014398616"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1014421541"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1014401683"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1014394726"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1014380606"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1014384571"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Ghost.Name = "A_Ghost"
	A_Ghost.Parent = SpecialTab
	A_Ghost.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Ghost.BorderSizePixel = 0
	A_Ghost.Position = UDim2.new(0, 0, 0.900632322, 0)
	A_Ghost.Size = UDim2.new(0, 150, 0, 30)
	A_Ghost.Font = Enum.Font.SciFi
	A_Ghost.Text = "Ghost"
	A_Ghost.TextColor3 = Color3.new(1, 1, 1)
	A_Ghost.TextSize = 20
	A_Ghost.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
		Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
		Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Sneaky.Name = "A_Sneaky"
	A_Sneaky.Parent = SpecialTab
	A_Sneaky.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Sneaky.BorderSizePixel = 0
	A_Sneaky.Position = UDim2.new(0, 0, 0.517628431, 0)
	A_Sneaky.Size = UDim2.new(0, 150, 0, 30)
	A_Sneaky.Font = Enum.Font.SciFi
	A_Sneaky.Text = "Sneaky"
	A_Sneaky.TextColor3 = Color3.new(1, 1, 1)
	A_Sneaky.TextSize = 20
	A_Sneaky.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1132473842"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1132477671"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1132510133"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1132494274"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1132489853"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1132461372"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1132469004"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Princess.Name = "A_Princess"
	A_Princess.Parent = SpecialTab
	A_Princess.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Princess.BorderSizePixel = 0
	A_Princess.Position = UDim2.new(0, 0, 0.645296335, 0)
	A_Princess.Size = UDim2.new(0, 150, 0, 30)
	A_Princess.Font = Enum.Font.SciFi
	A_Princess.Text = "Princess"
	A_Princess.TextColor3 = Color3.new(1, 1, 1)
	A_Princess.TextSize = 20
	A_Princess.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	Category_2.Name = "Category"
	Category_2.Parent = SpecialTab
	Category_2.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
	Category_2.BorderSizePixel = 0
	Category_2.Size = UDim2.new(0, 150, 0, 30)
	Category_2.Text = "Special"
	Category_2.TextColor3 = Color3.new(0, 0.835294, 1)
	Category_2.TextSize = 14

	OtherTab.Name = "OtherTab"
	OtherTab.Parent = Main
	OtherTab.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
	OtherTab.BackgroundTransparency = 1
	OtherTab.BorderSizePixel = 0
	OtherTab.Position = UDim2.new(0, 0, 1.06800008, 0)
	OtherTab.Size = UDim2.new(0, 150, 0, 220)

	Category_3.Name = "Category"
	Category_3.Parent = OtherTab
	Category_3.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
	Category_3.BorderSizePixel = 0
	Category_3.Size = UDim2.new(0, 150, 0, 30)
	Category_3.Text = "Other"
	Category_3.TextColor3 = Color3.new(0, 0.835294, 1)
	Category_3.TextSize = 14

	A_None.Name = "A_None"
	A_None.Parent = OtherTab
	A_None.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_None.BorderSizePixel = 0
	A_None.Position = UDim2.new(0, 0, 0.134545445, 0)
	A_None.Size = UDim2.new(0, 150, 0, 30)
	A_None.Font = Enum.Font.SciFi
	A_None.Text = "None"
	A_None.TextColor3 = Color3.new(1, 1, 1)
	A_None.TextSize = 20
	A_None.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
		Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	A_Anthro.Name = "A_Anthro"
	A_Anthro.Parent = OtherTab
	A_Anthro.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	A_Anthro.BorderSizePixel = 0
	A_Anthro.Position = UDim2.new(0, 0, 0.269090891, 0)
	A_Anthro.Size = UDim2.new(0, 150, 0, 30)
	A_Anthro.Font = Enum.Font.SciFi
	A_Anthro.Text = "Anthro (Default)"
	A_Anthro.TextColor3 = Color3.new(1, 1, 1)
	A_Anthro.TextSize = 20
	A_Anthro.MouseButton1Click:Connect(function()
		Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
		Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
		Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
		Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
		Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
		Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
		Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
		game.Players.LocalPlayer.Character.Humanoid.Jump = true
	end)

	wait(1)
	Main:TweenPosition(UDim2.new(0.421999991, 0, 0.28400004, 0))
end)


UICorner_20.Parent = AllAnimations

AllEmotes.Name = "AllEmotes"
AllEmotes.Parent = Page2Frame
AllEmotes.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
AllEmotes.Position = UDim2.new(0.504717112, 0, 0.688311696, 0)
AllEmotes.Size = UDim2.new(0, 94, 0, 34)
AllEmotes.Font = Enum.Font.SourceSans
AllEmotes.Text = "All Emotes"
AllEmotes.TextColor3 = Color3.fromRGB(0, 193, 0)
AllEmotes.TextSize = 20.000
AllEmotes.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Emotes Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	-- Write /e print and look at console for emotes
	-- not my script / i wont have v3rm thread srry guys
	-- God


	if msg == "/e god" then
		AnimationId = "3337994105"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Happy
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e happy" then
		AnimationId = "4841405708"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Sad
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e sad" then
		AnimationId = "4841407203"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Monkey
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e monkey" then
		AnimationId = "3333499508"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Baby Dance
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e baby" then
		AnimationId = "4265725525"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Line Dance
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e line" then
		AnimationId = "4049037604"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Fashionable
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e fashion" then
		AnimationId = "3333331310"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Twirl
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e twirl" then
		AnimationId = "3334968680"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Top Rock
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e top" then
		AnimationId = "3361276673"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Dizzy
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e dizzy" then
		AnimationId = "3361426436"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Shy
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e shy" then
		AnimationId = "3337978742"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Side to Side
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e side" then
		AnimationId = "3333136415"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Dorky Dance
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e dorky" then
		AnimationId = "4212455378"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Robot
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e robot" then
		AnimationId = "3338025566"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Shuffle
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e shuffle" then
		AnimationId = "4349242221"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Around Town
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e around" then
		AnimationId = "3303391864"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- T
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e t" then
		AnimationId = "3338010159"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Bodybuilder
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e body" then
		AnimationId = "3333387824"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Fancy Feet
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e fancy" then
		AnimationId = "3333432454"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Celebrate
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e celebrate" then
		AnimationId = "3338097973"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Idol
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e idol" then
		AnimationId = "4101966434"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Fast Hands
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e fast" then
		AnimationId = "4265701731"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Haha
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e haha" then
		AnimationId = "3337966527"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Curtsy
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e curtsy" then
		AnimationId = "4555816777"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Air Dance
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e air" then
		AnimationId = "4555782893"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Zombie
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e zombie" then
		AnimationId = "4210116953"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Tree
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e tree" then
		AnimationId = "4049551434"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Swoosh
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e swoosh" then
		AnimationId = "3361481910"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Greatest
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e great" then
		AnimationId = "3338042785"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Sneaky
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e sneaky" then
		AnimationId = "3334424322"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Jacks
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e jacks" then
		AnimationId = "3338066331"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Get Out
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e out" then
		AnimationId = "3333272779"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Fishing
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e fish" then
		AnimationId = "3334832150"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Louder
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e loud" then
		AnimationId = "3338083565"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Y
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e y" then
		AnimationId = "4349285876"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Borock's Rage
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e borock" then
		AnimationId = "3236842542"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Ud'zal's Summoning
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e udzal" then
		AnimationId = "3303161675"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Sleep
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e sleep" then
		AnimationId = "4686925579"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Disagree
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e disagree" then
		AnimationId = "4841401869"
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://"..AnimationId
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play(0)
		k:AdjustSpeed(1)
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		game.Players.LocalPlayer.Character.Humanoid.Running:connect(function(speed)
			if speed > 0 then
				game.Players.LocalPlayer.Character.Animate.Disabled = false
				k:Stop(0)
			end
		end)
	end
end)

-- Printing emote names
game.Players.LocalPlayer.Chatted:connect(function(msg)
	if msg == "/e print" then
		print("God = /e god")
		print("Happy = /e happy")
		print("Sad = /e sad")
		print("Monkey = /e monkey")
		print("Baby Dance = /e baby")
		print("Line Dance = /e line")
		print("Fashionable = /e fashion")
		print("Twirl = /e twirl")
		print("Top Rock = /e top")
		print("Dizzy = /e dizzy")
		print("Shy = /e shy")
		print("Side to Side = /e side")
		print("Dorky Dance = /e dorky")
		print("Robot = /e robot")
		print("Shuffle = /e shuffle")
		print("Around Town = /e around")
		print("T = /e t")
		print("Bodybuilder = /e body")
		print("Fancy Feet = /e fancy")
		print("Celebrate = /e celebrate")
		print("Idol = /e idol")
		print("Fast Hands = /e fast")
		print("Haha = /e haha")
		print("Curtsy = /e curtsy")
		print("Air Dance = /e air")
		print("Zombie = /e zombie")
		print("Tree = /e tree")
		print("Swoosh = /e swoosh")
		print("Greatest = /e great")
		print("Sneaky = /e sneaky")
		print("Jacks = /e jacks")
		print("Get Out = /e out")
		print("Fishing = /e fish")
		print("Louder = /e loud")
		print("Y = /e y")
		print("Borock's Rage = /e borock")
		print("Ud'zal's Summoning = /e udzal")
		print("Sleep = /e sleep")
		print("Disagree = /e disagree")
	end
end)															


UICorner_21.Parent = AllEmotes

Naked.Name = "Naked"
Naked.Parent = Page2Frame
Naked.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Naked.Position = UDim2.new(0.011792453, 0, 0.688311696, 0)
Naked.Size = UDim2.new(0, 98, 0, 34)
Naked.Font = Enum.Font.SourceSans
Naked.Text = "Naked"
Naked.TextColor3 = Color3.fromRGB(0, 193, 0)
Naked.TextSize = 20.000
Naked.MouseButton1Down:connect(function()
	wait(0) local A_1 = "EwEw" local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	game.Players.LocalPlayer.Character.Pants:Destroy()
	game.Players.LocalPlayer.Character.Shirt:Destroy()
end)

UICorner_22.Parent = Naked

ToolReach.Name = "ToolReach"
ToolReach.Parent = Page2Frame
ToolReach.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
ToolReach.Position = UDim2.new(0.745283008, 0, 0.688311696, 0)
ToolReach.Size = UDim2.new(0, 95, 0, 34)
ToolReach.Font = Enum.Font.SourceSans
ToolReach.Text = "All Reach"
ToolReach.TextColor3 = Color3.fromRGB(0, 193, 0)
ToolReach.TextSize = 20.000
ToolReach.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Reach Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
		if v:isA("Tool") then
			local a = Instance.new("SelectionBox",v.Handle)
			a.Adornee = v.Handle
			v.Handle.Size = Vector3.new(50,50,50)
			v.GripPos = Vector3.new(10,10,10)
			v.Handle.Transparency = 1
			lplayer.Character.Humanoid:UnequipTools()
		end
	end
end)

UICorner_23.Parent = ToolReach

GodBlock.Name = "GodBlock"
GodBlock.Parent = Page2Frame
GodBlock.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
GodBlock.Position = UDim2.new(0.745283067, 0, 0.38961041, 0)
GodBlock.Size = UDim2.new(0, 98, 0, 34)
GodBlock.Font = Enum.Font.SourceSans
GodBlock.Text = "GodBlock"
GodBlock.TextColor3 = Color3.fromRGB(0, 193, 0)
GodBlock.TextSize = 20.000
GodBlock.MouseButton1Down:connect(function()
	wait(0) local A_1 = "GodBlock Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	loadstring(game:HttpGet("https://pastebin.com/raw/8dYyXr7n", true))()
end)

UICorner_24.Parent = GodBlock

AntiSlow.Name = "AntiSlow"
AntiSlow.Parent = Page2Frame
AntiSlow.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
AntiSlow.Position = UDim2.new(0.747641563, 0, 0.0844156072, 0)
AntiSlow.Size = UDim2.new(0, 98, 0, 34)
AntiSlow.Font = Enum.Font.SourceSans
AntiSlow.Text = "AntiSlow"
AntiSlow.TextColor3 = Color3.fromRGB(0, 193, 0)
AntiSlow.TextSize = 20.000
AntiSlow.MouseButton1Down:connect(function()
	wait(0) local A_1 = "AntiSlow Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	loadstring(game:HttpGet("https://pastebin.com/raw/a6r7Qhch", true))()
end)

UICorner_25.Parent = AntiSlow

AntiFlash.Name = "AntiFlash"
AntiFlash.Parent = Page2Frame
AntiFlash.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
AntiFlash.Position = UDim2.new(0.504717052, 0, 0.0844156072, 0)
AntiFlash.Size = UDim2.new(0, 98, 0, 34)
AntiFlash.Font = Enum.Font.SourceSans
AntiFlash.Text = "AntiFlash"
AntiFlash.TextColor3 = Color3.fromRGB(0, 193, 0)
AntiFlash.TextSize = 20.000
AntiFlash.MouseButton1Down:connect(function()
	wait(0) local A_1 = "AntiFlashBang Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	while true do
		local XD = game:GetService("Players").LocalPlayer.PlayerGui.MainScreenGui

		if XD:FindFirstChild("whiteScreen") then
			XD.whiteScreen:Destroy()
		end
		wait(0.2)
	end
end)


UICorner_26.Parent = AntiFlash

Floatfists.Name = "Floatfists"
Floatfists.Parent = Page2Frame
Floatfists.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Floatfists.Position = UDim2.new(0.254717052, 0, 0.383116901, 0)
Floatfists.Size = UDim2.new(0, 98, 0, 34)
Floatfists.Font = Enum.Font.SourceSans
Floatfists.Text = "FloatFists"
Floatfists.TextColor3 = Color3.fromRGB(0, 193, 0)
Floatfists.TextSize = 20.000
Floatfists.MouseButton1Down:connect(function()
	wait(0) local A_1 = "FloatFists Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	-- // Da Hood Free Fist by Misamiru#8232
	-- // If your hand dissapears just respawn and re-execute

	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")

	local LocalPlayer = Players.LocalPlayer
	local Mouse = LocalPlayer:GetMouse()

	local Character = LocalPlayer.Character
	local RightHand = Character.RightHand

	wait(3)

	local Box = Instance.new("SelectionBox")
	Box.LineThickness = 0.15
	Box.Color3 = Color3.new(0, 255, 0)
	Box.Transparency = 0.50
	Box.Adornee = RightHand
	Box.Parent = RightHand

	RightHand.RightWrist:Destroy() -- so it doesn't move weirdly with the animations

	while true do -- // idk why it doesn't replicate with RenderStepped
		pcall(function()
			RightHand.Position = Mouse.Hit.p
			RightHand.Rotation = Vector3.new(0,0,0)
			RightHand.Massless = true
		end)
		pcall(function()
			local Tool = Character:FindFirstChildOfClass("Tool")
			Tool.Handle.Position = RightHand.Position
		end)
		RunService.RenderStepped:Wait()
	end
end)

UICorner_27.Parent = Floatfists

GodBullet.Name = "GodBullet"
GodBullet.Parent = Page2Frame
GodBullet.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
GodBullet.Position = UDim2.new(0.50000006, 0, 0.38961041, 0)
GodBullet.Size = UDim2.new(0, 98, 0, 34)
GodBullet.Font = Enum.Font.SourceSans
GodBullet.Text = "GodBullet"
GodBullet.TextColor3 = Color3.fromRGB(0, 193, 0)
GodBullet.TextSize = 20.000
GodBullet.MouseButton1Down:connect(function()
	wait(0) local A_1 = "GodBullet Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

	local ps = game:GetService("Players")
	local lp = ps.LocalPlayer
	local char = lp.Character

	char.BodyEffects.Armor:Destroy()
	char.BodyEffects.Defense:Destroy()

	local Clone1 = Instance.new("IntValue")
	Clone1.Name = "Armor"
	Clone1.Parent = char.BodyEffects

	local Clone2 = Instance.new("NumberValue")
	Clone2.Name = "Defense"
	Clone2.Parent = char.BodyEffects
end)


UICorner_28.Parent = GodBullet

Headless.Name = "Headless"
Headless.Parent = Page2Frame
Headless.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Headless.Position = UDim2.new(0.0117924809, 0, 0.38961041, 0)
Headless.Size = UDim2.new(0, 98, 0, 34)
Headless.Font = Enum.Font.SourceSans
Headless.Text = "Headless"
Headless.TextColor3 = Color3.fromRGB(0, 193, 0)
Headless.TextSize = 20.000
Headless.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Headless Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 

	pcall(function()
		game.Players.LocalPlayer.Character.Head.Neck:Destroy()
		game.Players.LocalPlayer.Character.UpperTorso.NeckAttachment:Destroy()
		game.Players.LocalPlayer.Character.Humanoid.HealthDisplayDistance = math.huge
		game.Players.LocalPlayer.Character.Humanoid.NameDisplayDistance = math.huge
		game.Players.LocalPlayer.Character.Head.Size = Vector3.new(0,0,0)
		game.Players.LocalPlayer.Character.Head.Massless = true
		game.Players.LocalPlayer.Character.Head.CanCollide = false

		heazd = true

		while heazd == true do 
			pcall(function()  
				game.Players.LocalPlayer.Character.Head.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
				game.Players.LocalPlayer.Character.UpperTorso.NeckRigAttachment.CFrame =  CFrame.new(0, 100000.4736328125, 0)
				game.Players.LocalPlayer.Character.Head.CFrame = CFrame.new(0, 100000.4736328125, 0)
			end)
			wait()
		end
	end)
end)

UICorner_29.Parent = Headless

Tornado.Name = "Tornado"
Tornado.Parent = Page2Frame
Tornado.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Tornado.Position = UDim2.new(0.257075489, 0, 0.0844156072, 0)
Tornado.Size = UDim2.new(0, 98, 0, 34)
Tornado.Font = Enum.Font.SourceSans
Tornado.Text = "Tornado"
Tornado.TextColor3 = Color3.fromRGB(0, 193, 0)
Tornado.TextSize = 20.000
Tornado.MouseButton1Down:connect(function()
	wait(0) local A_1 = "Tornado Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	pcall(function()
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v.Name == '[Knife]' then
				v.Parent = game.Players.LocalPlayer.Character
			end
		end
	end)
	wait(.9)
	local targetpos = CFrame.new(-278.063446, 21.75, -240.871841)
	local plr = game.Players.LocalPlayer
	local pos = plr.Character.HumanoidRootPart.Position
	if not game.Players.LocalPlayer.Character:FindFirstChild("[Knife]") then
		plr.Character.HumanoidRootPart.CFrame = targetpos
		local cd = game:GetService("Workspace").Ignored.Shop["[Knife] - $150"]:FindFirstChild("ClickDetector")
		wait(.9)
		fireclickdetector(cd)
		wait(.4)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripPos     = Vector3.new(2, -5, -1.5)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripForward     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripRight     = Vector3.new(1, 0, -3)
		game.Players.LocalPlayer.Backpack["[Knife]"].GripUp     = Vector3.new(0, 0, 0)
		game.Players.LocalPlayer.Backpack["[Knife]"].Parent = game.Players.LocalPlayer.Character
		spin = true
		local spinSpeed = 100
		local speaker = game.Players.LocalPlayer
		for i,v in pairs(speaker.Character.HumanoidRootPart:GetChildren()) do
			if v.Name == "Spinning" then
				v:Destroy()
			end
		end
		local Spin = Instance.new("BodyAngularVelocity", speaker.Character.HumanoidRootPart)
		Spin.Name = "Spinning"
		Spin.MaxTorque = Vector3.new(0, math.huge, 0)
		Spin.AngularVelocity = Vector3.new(0,spinSpeed,0)
		wait(0.6)
	end
end)

UICorner_30.Parent = Tornado

FistReach.Name = "FistReach"
FistReach.Parent = Page2Frame
FistReach.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
FistReach.Position = UDim2.new(0.0117924809, 0, 0.0844155997, 0)
FistReach.Size = UDim2.new(0, 98, 0, 34)
FistReach.Font = Enum.Font.SourceSans
FistReach.Text = "FistReach"
FistReach.TextColor3 = Color3.fromRGB(0, 193, 0)
FistReach.TextSize = 20.000
FistReach.MouseButton1Down:connect(function()
	LP = game.Players.LocalPlayer
	for i,v in ipairs(LP.Character:GetDescendants()) do
		if v:IsA("MeshPart") then v.Massless = true
			v.CanCollide = false
			v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)

		end
	end

	for i,v in ipairs(game.workspace:GetDescendants()) do
		if v:IsA("Seat") then 
			v.Disabled = true
		end
	end
	x = 35
	y = 35
	z = 35


	penis = Vector3.new(x,y,z)

	LP.Character.RightHand.Size = penis

	LP.Character.RightHand.Transparency = 1
	local selectionBox = Instance.new("SelectionBox",LP.Character.RightHand)
	selectionBox.Adornee = LP.Character.RightHand
	selectionBox.Color3 = Color3.new(0, 255, 0)

	LP.Character.LeftHand.Size = penis
	LP.Character.BodyEffects.SpecialParts.LeftHand.Size = penis

	LP.Character.LeftHand.Transparency = 1
	local selectionBox = Instance.new("SelectionBox",LP.Character.LeftHand)
	selectionBox.Adornee = LP.Character.LeftHand
	selectionBox.Color3 = Color3.new(0, 255, 0)
end)

UICorner_31.Parent = FistReach

Page3Frame.Name = "Page3Frame"
Page3Frame.Parent = MainFrame
Page3Frame.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
Page3Frame.BorderColor3 = Color3.fromRGB(98, 98, 98)
Page3Frame.Position = UDim2.new(0.0350877047, 0, 0.206896573, 0)
Page3Frame.Size = UDim2.new(0, 424, 0, 154)
Page3Frame.Visible = false

UICorner_32.Parent = Page3Frame

soon.Name = "soon"
soon.Parent = Page3Frame
soon.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon.Position = UDim2.new(0.257075489, 0, 0.688311696, 0)
soon.Size = UDim2.new(0, 96, 0, 34)
soon.Font = Enum.Font.SourceSans
soon.Text = "soon"
soon.TextColor3 = Color3.fromRGB(0, 193, 0)
soon.TextSize = 20.000

UICorner_33.Parent = soon

soon_2.Name = "soon"
soon_2.Parent = Page3Frame
soon_2.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_2.Position = UDim2.new(0.504717112, 0, 0.688311696, 0)
soon_2.Size = UDim2.new(0, 94, 0, 34)
soon_2.Font = Enum.Font.SourceSans
soon_2.Text = "soon"
soon_2.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_2.TextSize = 20.000

UICorner_34.Parent = soon_2

soon_3.Name = "soon"
soon_3.Parent = Page3Frame
soon_3.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_3.Position = UDim2.new(0.011792453, 0, 0.688311696, 0)
soon_3.Size = UDim2.new(0, 98, 0, 34)
soon_3.Font = Enum.Font.SourceSans
soon_3.Text = "soon"
soon_3.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_3.TextSize = 20.000

UICorner_35.Parent = soon_3

soon_4.Name = "soon"
soon_4.Parent = Page3Frame
soon_4.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_4.Position = UDim2.new(0.745283008, 0, 0.688311696, 0)
soon_4.Size = UDim2.new(0, 95, 0, 34)
soon_4.Font = Enum.Font.SourceSans
soon_4.Text = "soon"
soon_4.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_4.TextSize = 20.000

UICorner_36.Parent = soon_4

soon_5.Name = "soon"
soon_5.Parent = Page3Frame
soon_5.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_5.Position = UDim2.new(0.745283067, 0, 0.38961041, 0)
soon_5.Size = UDim2.new(0, 98, 0, 34)
soon_5.Font = Enum.Font.SourceSans
soon_5.Text = "soon"
soon_5.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_5.TextSize = 20.000

UICorner_37.Parent = soon_5

soon_6.Name = "soon"
soon_6.Parent = Page3Frame
soon_6.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_6.Position = UDim2.new(0.747641563, 0, 0.0844156072, 0)
soon_6.Size = UDim2.new(0, 98, 0, 34)
soon_6.Font = Enum.Font.SourceSans
soon_6.Text = "NoClip(e)"
soon_6.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_6.TextSize = 20.000
soon_6.MouseButton1Down:connect(function()
	wait(0) local A_1 = "NoClip Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	loadstring(game:HttpGet("https://pastebin.com/raw/GF9aCkVW", true))()
end)

UICorner_38.Parent = soon_6

soon_7.Name = "soon"
soon_7.Parent = Page3Frame
soon_7.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_7.Position = UDim2.new(0.504717052, 0, 0.0844156072, 0)
soon_7.Size = UDim2.new(0, 98, 0, 34)
soon_7.Font = Enum.Font.SourceSans
soon_7.Text = "Tp(q)"
soon_7.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_7.TextSize = 20.000
soon_7.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/gjWXkd1A", true))()
end)

UICorner_39.Parent = soon_7

soon_8.Name = "soon"
soon_8.Parent = Page3Frame
soon_8.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_8.Position = UDim2.new(0.254717052, 0, 0.383116901, 0)
soon_8.Size = UDim2.new(0, 98, 0, 34)
soon_8.Font = Enum.Font.SourceSans
soon_8.Text = "soon"
soon_8.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_8.TextSize = 20.000

UICorner_40.Parent = soon_8

soon_9.Name = "soon"
soon_9.Parent = Page3Frame
soon_9.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_9.Position = UDim2.new(0.50000006, 0, 0.38961041, 0)
soon_9.Size = UDim2.new(0, 98, 0, 34)
soon_9.Font = Enum.Font.SourceSans
soon_9.Text = "soon"
soon_9.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_9.TextSize = 20.000

UICorner_41.Parent = soon_9

soon_10.Name = "soon"
soon_10.Parent = Page3Frame
soon_10.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_10.Position = UDim2.new(0.0117924809, 0, 0.38961041, 0)
soon_10.Size = UDim2.new(0, 98, 0, 34)
soon_10.Font = Enum.Font.SourceSans
soon_10.Text = "soon"
soon_10.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_10.TextSize = 20.000

UICorner_42.Parent = soon_10

P90Farm.Name = "P90 Farm"
P90Farm.Parent = Page3Frame
P90Farm.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
P90Farm.Position = UDim2.new(0.257075489, 0, 0.0844156072, 0)
P90Farm.Size = UDim2.new(0, 98, 0, 34)
P90Farm.Font = Enum.Font.SourceSans
P90Farm.Text = "P90Farm"
P90Farm.TextColor3 = Color3.fromRGB(0, 193, 0)
P90Farm.TextSize = 20.000
P90Farm.MouseButton1Down:connect(function()
	wait(0) local A_1 = "P90AutoFarm Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	loadstring(game:HttpGet('https://raw.githubusercontent.com/tayodevelup/sadasdasdasdas/master/autorob'))()
end)

UICorner_43.Parent = P90Farm

soon_11.Name = "soon"
soon_11.Parent = Page3Frame
soon_11.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
soon_11.Position = UDim2.new(0.0117924809, 0, 0.0844155997, 0)
soon_11.Size = UDim2.new(0, 98, 0, 34)
soon_11.Font = Enum.Font.SourceSans
soon_11.Text = "Autofarm"
soon_11.TextColor3 = Color3.fromRGB(0, 193, 0)
soon_11.TextSize = 20.000
soon_11.MouseButton1Down:connect(function()
	wait(0) local A_1 = "AutoFarm Enabled By SamX." local A_2 = "All" local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest Event:FireServer(A_1, A_2) 
	loadstring(game:HttpGet("https://pastebin.com/raw/74VJ07iY", true))()
end)

UICorner_44.Parent = soon_11

TpPageButton_2.Name = "TpPageButton"
TpPageButton_2.Parent = MainFrame
TpPageButton_2.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
TpPageButton_2.BorderColor3 = Color3.fromRGB(98, 98, 98)
TpPageButton_2.Position = UDim2.new(0.0350876749, 0, 0.202586234, 0)
TpPageButton_2.Size = UDim2.new(0, 424, 0, 154)
TpPageButton_2.Visible = false

UICorner_45.Parent = TpPageButton_2

GunShop1.Name = "GunShop1"
GunShop1.Parent = TpPageButton_2
GunShop1.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
GunShop1.Position = UDim2.new(0.257075489, 0, 0.688311696, 0)
GunShop1.Size = UDim2.new(0, 96, 0, 34)
GunShop1.Font = Enum.Font.SourceSans
GunShop1.Text = "GunShop1"
GunShop1.TextColor3 = Color3.fromRGB(0, 193, 0)
GunShop1.TextSize = 20.000
GunShop1.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(-582, 7.172, -739.015)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_46.Parent = GunShop1

GunShop2.Name = "GunShop2"
GunShop2.Parent = TpPageButton_2
GunShop2.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
GunShop2.Position = UDim2.new(0.504717112, 0, 0.688311696, 0)
GunShop2.Size = UDim2.new(0, 94, 0, 34)
GunShop2.Font = Enum.Font.SourceSans
GunShop2.Text = "GunShop2"
GunShop2.TextColor3 = Color3.fromRGB(0, 193, 0)
GunShop2.TextSize = 20.000
GunShop2.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(481.313, 47.64, -623.539)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_47.Parent = GunShop2

UFO.Name = "UFO"
UFO.Parent = TpPageButton_2
UFO.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
UFO.Position = UDim2.new(0.011792453, 0, 0.688311696, 0)
UFO.Size = UDim2.new(0, 98, 0, 34)
UFO.Font = Enum.Font.SourceSans
UFO.Text = "UFO"
UFO.TextColor3 = Color3.fromRGB(0, 193, 0)
UFO.TextSize = 20.000
UFO.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(71.565, 142.926, -690.33)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_48.Parent = UFO

Admin.Name = "Admin"
Admin.Parent = TpPageButton_2
Admin.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Admin.Position = UDim2.new(0.745283008, 0, 0.688311696, 0)
Admin.Size = UDim2.new(0, 95, 0, 34)
Admin.Font = Enum.Font.SourceSans
Admin.Text = "AdminBase"
Admin.TextColor3 = Color3.fromRGB(0, 193, 0)
Admin.TextSize = 20.000
Admin.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(-729.895, -37.642, -885.8)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_49.Parent = Admin

PhoneShop.Name = "PhoneShop"
PhoneShop.Parent = TpPageButton_2
PhoneShop.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
PhoneShop.Position = UDim2.new(0.747641563, 0, 0.0844156072, 0)
PhoneShop.Size = UDim2.new(0, 98, 0, 34)
PhoneShop.Font = Enum.Font.SourceSans
PhoneShop.Text = "PhoneShop"
PhoneShop.TextColor3 = Color3.fromRGB(0, 193, 0)
PhoneShop.TextSize = 20.000
PhoneShop.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(-120.121, 22.946, -870.425)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_50.Parent = PhoneShop

MaskShop.Name = "MaskShop"
MaskShop.Parent = TpPageButton_2
MaskShop.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
MaskShop.Position = UDim2.new(0.504717052, 0, 0.0844156072, 0)
MaskShop.Size = UDim2.new(0, 98, 0, 34)
MaskShop.Font = Enum.Font.SourceSans
MaskShop.Text = "MaskShop"
MaskShop.TextColor3 = Color3.fromRGB(0, 193, 0)
MaskShop.TextSize = 20.000
MaskShop.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(-210.255, 21.674, -823.16)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_51.Parent = MaskShop

Prison.Name = "Prison"
Prison.Parent = TpPageButton_2
Prison.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Prison.Position = UDim2.new(0.257075489, 0, 0.0844156072, 0)
Prison.Size = UDim2.new(0, 98, 0, 34)
Prison.Font = Enum.Font.SourceSans
Prison.Text = "Prison"
Prison.TextColor3 = Color3.fromRGB(0, 193, 0)
Prison.TextSize = 20.000
Prison.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(-294.162, 22.644, -111.716)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_52.Parent = Prison

Bank.Name = "Bank"
Bank.Parent = TpPageButton_2
Bank.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
Bank.Position = UDim2.new(0.0117924809, 0, 0.0844155997, 0)
Bank.Size = UDim2.new(0, 98, 0, 34)
Bank.Font = Enum.Font.SourceSans
Bank.Text = "Bank"
Bank.TextColor3 = Color3.fromRGB(0, 193, 0)
Bank.TextSize = 20.000
Bank.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(-415.661, 22.22, -284.6)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)

UICorner_53.Parent = Bank

line.Name = "line"
line.Parent = TpPageButton_2
line.BackgroundColor3 = Color3.fromRGB(113, 113, 113)
line.BorderColor3 = Color3.fromRGB(113, 113, 113)
line.Position = UDim2.new(0, 0, 0.402597398, 0)
line.Size = UDim2.new(0, 424, 0, 29)

UICorner_54.Parent = line

local hotkey             = "v" -- must be lowercase
local mouse              = game.Players.LocalPlayer:GetMouse()



mouse.KeyDown:Connect(function(key)
	if key == hotkey then
		if MainFrame.Visible then
			MainFrame.Visible = not MainFrame.Visible
		else
			MainFrame.Visible = true
		end
	end
end)-- change Main to ur frame name

--/ Functions

function GetShortenedPlrFromName(name) -- uses string.sub to see if the typed in name fits and matches somewhere in the player's name, uncase sensitive. returns a table where the player is inside because of the all and others support
	name = string.lower(tostring(name))

	if not game:GetService("Players"):FindFirstChild("all") and name == "all" or game:GetService("Players"):FindFirstChild("all") and game:GetService("Players"):FindFirstChild("all").ClassName ~= "Player" and name == "all" then
		return game:GetService("Players"):GetPlayers()
	end
	if not game:GetService("Players"):FindFirstChild("others") and name == "others" or game:GetService("Players"):FindFirstChild("others") and game:GetService("Players"):FindFirstChild("others").ClassName ~= "Player" and name == "others" then
		name = game:GetService("Players"):GetPlayers()
		for i, v in pairs(name) do
			if v == LocalPlayer then
				table.remove(name, i)
			end
		end
		return name
	end

	for i, v in pairs(game.Players:GetPlayers()) do
		if string.lower(string.sub(v.Name, 1, #name)) == name then
			return {v}
		end
	end

	return nil
end



--/ Main

LockBtn.MouseButton1Down:Connect(function()
	if GetShortenedPlrFromName(TextBox.Text) ~= nil then
		for i, v in pairs(GetShortenedPlrFromName(TextBox.Text)) do
			LockedPlayer = v
			break
		end
	end
end)

UnLockBtn.MouseButton1Down:Connect(function()
	LockedPlayer = nil
end)

game:GetService("RunService").Heartbeat:Connect(function()
	if LockedPlayer ~= nil and LockedPlayer.Character and LockedPlayer.Character:FindFirstChildOfClass("Humanoid") and LockedPlayer.Character:FindFirstChildOfClass("Humanoid").Health > 0 then
		for i, v in pairs(LocalPlayer.Character:GetDescendants()) do
			if v.ClassName == "Motor6D" and (v.Name == "RightWrist" or v.Name == "LeftWrist") then
				v:Destroy()
			end
		end
		if LocalPlayer ~= nil and LocalPlayer.Character and LocalPlayer.Character:FindFirstChild("RightHand") and LocalPlayer.Character:FindFirstChild("LeftHand") and LocalPlayer.Character:FindFirstChildOfClass("Humanoid") and LocalPlayer.Character:FindFirstChildOfClass("Humanoid").Health > 0 then

			if LockedPlayer.Character.PrimaryPart and not LockedPlayer.Character:FindFirstChild("HumanoidRootPart") then
				LocalPlayer.Character.RightHand.CFrame = LockedPlayer.Character.PrimaryPart.CFrame
				LocalPlayer.Character.LeftHand.CFrame = LockedPlayer.Character.PrimaryPart.CFrame
			elseif LockedPlayer.Character:FindFirstChild("HumanoidRootPart") then
				LocalPlayer.Character.RightHand.CFrame = LockedPlayer.Character.HumanoidRootPart.CFrame
				LocalPlayer.Character.LeftHand.CFrame = LockedPlayer.Character.HumanoidRootPart.CFrame
			end

		end
	end
end)
