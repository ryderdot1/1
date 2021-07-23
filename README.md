-- Gui to Lua
-- Version: 3.2

-- Instances:

local SoloX = Instance.new("ScreenGui")
local Base = Instance.new("Frame")
local Outline = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local Noclip = Instance.new("TextButton")
local Frame = Instance.new("Frame")
local OtherScripts = Instance.new("TextLabel")
local Speed = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local Credits = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local Invisible = Instance.new("TextButton")
local Fling = Instance.new("TextButton")
local VR = Instance.new("TextButton")
local InfiniteJump = Instance.new("TextButton")

--Properties:

SoloX.Name = "Solo X"
SoloX.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
SoloX.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Base.Name = "Base"
Base.Parent = SoloX
Base.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Base.Position = UDim2.new(0.374303073, 0, 0.154904515, 0)
Base.Size = UDim2.new(0, 660, 0, 300)

Outline.Name = "Outline"
Outline.Parent = Base
Outline.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Outline.Position = UDim2.new(-0.00187100493, 0, -0.0241935216, 0)
Outline.Size = UDim2.new(0, 661, 0, 307)

TextLabel.Parent = Outline
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.Position = UDim2.new(8.46261215, 0, 22.7737007, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 30)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Solo X v0.1"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 50.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)

UICorner.CornerRadius = UDim.new(0, 15)
UICorner.Parent = Outline

UICorner_2.CornerRadius = UDim.new(0, 15)
UICorner_2.Parent = Base

Noclip.Name = "Noclip"
Noclip.Parent = Base
Noclip.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
Noclip.BorderSizePixel = 3
Noclip.Position = UDim2.new(0.178270757, 0, 0.256942958, 0)
Noclip.Size = UDim2.new(0.145670295, 0, 0.126666605, 0)
Noclip.Font = Enum.Font.Cartoon
Noclip.Text = "V TO NOCLIP"
Noclip.TextColor3 = Color3.fromRGB(0, 0, 0)
Noclip.TextSize = 14.000

Frame.Parent = Base
Frame.BackgroundColor3 = Color3.fromRGB(10, 44, 14)
Frame.Position = UDim2.new(0, 0, 0.550000012, 0)
Frame.Size = UDim2.new(0, 658, 0, 20)

OtherScripts.Name = "Other Scripts"
OtherScripts.Parent = Frame
OtherScripts.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
OtherScripts.BorderColor3 = Color3.fromRGB(53, 83, 104)
OtherScripts.Position = UDim2.new(0.00151975686, 0, 0, 0)
OtherScripts.Size = UDim2.new(0, 659, 0, 26)
OtherScripts.Font = Enum.Font.SourceSans
OtherScripts.Text = "Other Scripts"
OtherScripts.TextColor3 = Color3.fromRGB(255, 255, 255)
OtherScripts.TextSize = 26.000

Speed.Name = "Speed"
Speed.Parent = Base
Speed.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
Speed.BorderSizePixel = 3
Speed.Position = UDim2.new(0.341907114, 0, 0.256942958, 0)
Speed.Size = UDim2.new(0.145670295, 0, 0.126666605, 0)
Speed.Font = Enum.Font.Cartoon
Speed.Text = "SPEED"
Speed.TextColor3 = Color3.fromRGB(0, 0, 0)
Speed.TextSize = 14.000

Fly.Name = "Fly"
Fly.Parent = Base
Fly.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
Fly.BorderSizePixel = 3
Fly.Position = UDim2.new(0.014634381, 0, 0.256942958, 0)
Fly.Size = UDim2.new(0.145670295, 0, 0.126666605, 0)
Fly.Font = Enum.Font.Cartoon
Fly.Text = "E TO FLY"
Fly.TextColor3 = Color3.fromRGB(0, 0, 0)
Fly.TextSize = 14.000

Credits.Name = "Credits"
Credits.Parent = Fly
Credits.BackgroundColor3 = Color3.fromRGB(29, 29, 29)
Credits.BorderColor3 = Color3.fromRGB(180, 180, 180)
Credits.Position = UDim2.new(-0.0938535333, 0, -0.769495249, 0)
Credits.Size = UDim2.new(0, 660, 0, 21)

Title.Name = "Title"
Title.Parent = Credits
Title.Active = true
Title.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Title.BorderColor3 = Color3.fromRGB(24, 24, 24)
Title.Position = UDim2.new(0.0167019926, 0, -2.28571439, 0)
Title.Size = UDim2.new(0, 640, 0, 43)
Title.Font = Enum.Font.SourceSans
Title.Text = "Solo X"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextSize = 53.000
Title.TextWrapped = true

Invisible.Name = "Invisible"
Invisible.Parent = Base
Invisible.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
Invisible.BorderSizePixel = 3
Invisible.Position = UDim2.new(0.50402832, 0, 0.256942958, 0)
Invisible.Size = UDim2.new(0.145670295, 0, 0.126666605, 0)
Invisible.Font = Enum.Font.Cartoon
Invisible.Text = "INVISIBLE"
Invisible.TextColor3 = Color3.fromRGB(0, 0, 0)
Invisible.TextSize = 14.000

Fling.Name = "Fling"
Fling.Parent = Base
Fling.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
Fling.BorderSizePixel = 3
Fling.Position = UDim2.new(0.664634347, 0, 0.256942958, 0)
Fling.Size = UDim2.new(0.145670295, 0, 0.126666605, 0)
Fling.Font = Enum.Font.Cartoon
Fling.Text = "FLING"
Fling.TextColor3 = Color3.fromRGB(0, 0, 0)
Fling.TextSize = 14.000

VR.Name = "VR"
VR.Parent = Base
VR.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
VR.BorderSizePixel = 3
VR.Position = UDim2.new(0.0176646374, 0, 0.420276284, 0)
VR.Size = UDim2.new(0.14567031, 0, 0.0997237861, 0)
VR.Font = Enum.Font.Cartoon
VR.Text = "VR"
VR.TextColor3 = Color3.fromRGB(0, 0, 0)
VR.TextSize = 14.000

InfiniteJump.Name = "Infinite Jump"
InfiniteJump.Parent = Base
InfiniteJump.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
InfiniteJump.BorderSizePixel = 3
InfiniteJump.Position = UDim2.new(0.822210073, 0, 0.256942958, 0)
InfiniteJump.Size = UDim2.new(0.145670295, 0, 0.126666605, 0)
InfiniteJump.Font = Enum.Font.Cartoon
InfiniteJump.Text = "R TO INF JUMP"
InfiniteJump.TextColor3 = Color3.fromRGB(0, 0, 0)
InfiniteJump.TextSize = 14.000

-- Scripts:

local function UYSZL_fake_script() -- Base.ConfigX 
	local script = Instance.new('LocalScript', Base)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
	
end
coroutine.wrap(UYSZL_fake_script)()
local function GFSLAB_fake_script() -- Base.Reloader 
	local script = Instance.new('Script', Base)

	script.Parent.Visible = true
	wait(0.01)
	script.Parent.Visible = true
	
end
coroutine.wrap(GFSLAB_fake_script)()
local function MOPKLE_fake_script() -- Noclip.Noclip Script 
	local script = Instance.new('LocalScript', Noclip)

	script.Parent.MouseButton1Click:Connect(function()
		
	end)
		noclip = false
	game:GetService('RunService').Stepped:connect(function()
		if noclip then
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	plr = game.Players.LocalPlayer
	mouse = plr:GetMouse()
	mouse.KeyDown:connect(function(key)
	
		if key == "v" then
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	print('Loaded')
	print('Press "v" to noclip')
	
end
coroutine.wrap(MOPKLE_fake_script)()
local function VJXEJ_fake_script() -- Noclip.Button Script 
	local script = Instance.new('LocalScript', Noclip)

	--Button Script--
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Visible = true --Feel Free To Delete This If You Want To Keep Gui--
	end)
	
end
coroutine.wrap(VJXEJ_fake_script)()
local function ZVHAS_fake_script() -- Speed.Speed Script 
	local script = Instance.new('LocalScript', Speed)

	script.Parent.MouseButton1Click:Connect(function()
		if game.Players.LocalPlayer.Character.Humanoid.WalkSpeed == 100 then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
		else
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
		end  
	end)
end
coroutine.wrap(ZVHAS_fake_script)()
local function IREW_fake_script() -- Speed.Button Script 
	local script = Instance.new('LocalScript', Speed)

	--Button Script--
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Visible = true --Feel Free To Delete This If You Want To Keep Gui--
	end)
	
end
coroutine.wrap(IREW_fake_script)()
local function HUZBRHK_fake_script() -- Fly.Flying Script 
	local script = Instance.new('LocalScript', Fly)

	--Flying Script--
	script.parent.MouseButton1Down:connect(function()
		repeat wait() 
		until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Head") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid") 
		local mouse = game.Players.LocalPlayer:GetMouse() 
		repeat wait() until mouse
		local plr = game.Players.LocalPlayer 
		local torso = plr.Character.Head 
		local flying = true --Making This False Will Not Work In Mobile--
		local deb = true 
		local ctrl = {f = 0, b = 0, l = 0, r = 0} 
		local lastctrl = {f = 0, b = 0, l = 0, r = 0} 
		local maxspeed = 50 
		local speed = 0 
	
		function Fly() 
			local bg = Instance.new("BodyGyro", torso) 
			bg.P = 9e4 
			bg.maxTorque = Vector3.new(9e9, 9e9, 9e9) 
			bg.cframe = torso.CFrame 
			local bv = Instance.new("BodyVelocity", torso) 
			bv.velocity = Vector3.new(0,0.1,0) 
			bv.maxForce = Vector3.new(9e9, 9e9, 9e9) 
			repeat wait() 
				plr.Character.Humanoid.PlatformStand = true 
				if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then 
					speed = speed+.5+(speed/maxspeed) 
					if speed > maxspeed then 
						speed = maxspeed 
					end 
				elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then 
					speed = speed-1 
					if speed < 0 then 
						speed = 0 
					end 
				end 
				if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then 
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed 
					lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r} 
				elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then 
					bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed 
				else 
					bv.velocity = Vector3.new(0,0.1,0) 
				end 
				bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0) 
			until not flying 
			ctrl = {f = 0, b = 0, l = 0, r = 0} 
			lastctrl = {f = 0, b = 0, l = 0, r = 0} 
			speed = 0 
			bg:Destroy() 
			bv:Destroy() 
			plr.Character.Humanoid.PlatformStand = false 
		end 
		mouse.KeyDown:connect(function(key) 
			if key:lower() == "e" then 
				if flying then flying = false 
				else 
					flying = true 
					Fly() 
				end 
			elseif key:lower() == "w" then 
				ctrl.f = 1 
			elseif key:lower() == "s" then 
				ctrl.b = -1 
			elseif key:lower() == "a" then 
				ctrl.l = -1 
			elseif key:lower() == "d" then 
				ctrl.r = 1 
			end 
		end) 
		mouse.KeyUp:connect(function(key) 
			if key:lower() == "w" then 
				ctrl.f = 0 
			elseif key:lower() == "s" then 
				ctrl.b = 0 
			elseif key:lower() == "a" then 
				ctrl.l = 0 
			elseif key:lower() == "d" then 
				ctrl.r = 0 
			end 
		end)
		Fly()
	end)
end
coroutine.wrap(HUZBRHK_fake_script)()
local function GHYK_fake_script() -- Fly.Button Script 
	local script = Instance.new('LocalScript', Fly)

	--Button Script--
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Visible = true --Feel Free To Delete This If You Want To Keep Gui--
	end)
	
end
coroutine.wrap(GHYK_fake_script)()
local function KIXIMIO_fake_script() -- Invisible.Invisible Script 
	local script = Instance.new('LocalScript', Invisible)

	--Button Script--
	script.Parent.MouseButton1Click:Connect(function()
		for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
			if v:IsA("Shirt") or v:IsA("Pants") or v:IsA("Hat") then
				v:Destroy()
			end
			if v:IsA("Part") or v:IsA("MeshPart") then
				v.Transparency = 1
				if v.Name == "Head" then
					if v:FindFirstChild("face") then
						v.face:Destroy()
					end
				end
			end
		end --Feel Free To Delete This If You Want To Keep Gui--
	end)
end
coroutine.wrap(KIXIMIO_fake_script)()
local function WBUCL_fake_script() -- Fling.Fling Script 
	local script = Instance.new('LocalScript', Fling)

	--Button Script--
	script.Parent.MouseButton1Click:Connect(function()
		-- Spin script
	
		power = 700 -- change this to make it more or less powerful
	
		game:GetService('RunService').Stepped:connect(function()
			game.Players.LocalPlayer.Character.Head.CanCollide = false
			game.Players.LocalPlayer.Character.UpperTorso.CanCollide = false
			game.Players.LocalPlayer.Character.LowerTorso.CanCollide = false
			game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false
		end)
		wait(.1)
		local bambam = Instance.new("BodyThrust")
		bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		bambam.Force = Vector3.new(power,0,power)
		bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	
		-- Noclip Script
	
		local noclip = true -- Gets if you want the noclip
		char = game.Players.LocalPlayer.Character -- Gets your player
		while true do -- Make sure someone is in game
			if noclip == true then
				for _,v in pairs(char:children()) do
					pcall(function()
						if v.className == "Part" then
							v.CanCollide = false
						end
					end)
				end
			end
			game:service("RunService").Stepped:wait()
		end
	end)
end
coroutine.wrap(WBUCL_fake_script)()
local function HROQGJX_fake_script() -- VR.VR 
	local script = Instance.new('LocalScript', VR)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/drixpy/scr/main/README.md'),true))()
end
coroutine.wrap(HROQGJX_fake_script)()
local function FVSXWO_fake_script() -- InfiniteJump.Infinite Jump Script 
	local script = Instance.new('LocalScript', InfiniteJump)

	--Button Script--
	script.Parent.MouseButton1Click:Connect(function()
		-- by isaraw8912
		-- Press [R] to turn off and to turn on
	
		_G.infinjump = true
	
		local Player = game:GetService("Players").LocalPlayer
		local Mouse = Player:GetMouse()
		Mouse.KeyDown:connect(function(k)
			if _G.infinjump then
				if k:byte() == 32 then
					Humanoid = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
					Humanoid:ChangeState("Jumping")
					wait(0.1)
					Humanoid:ChangeState("Seated")
				end
			end
		end)
	
		local Player = game:GetService("Players").LocalPlayer
		local Mouse = Player:GetMouse()
		Mouse.KeyDown:connect(function(k)
			k = k:lower()
			if k == "r" then
				if _G.infinjump == true then
					_G.infinjump = false
				else
					_G.infinjump = true
				end
			end
		end)
	end)
end
coroutine.wrap(FVSXWO_fake_script)()
