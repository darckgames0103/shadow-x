-- shadow

local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local thebananadupe = Instance.new("TextButton")
local Momeh = Instance.new("TextButton")
local Ben = Instance.new("TextButton")
local Munehh = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local dupepop = Instance.new("TextButton")
local dupeamogusrb = Instance.new("TextButton")
local dupeloly = Instance.new("TextButton")
local dupethe = Instance.new("TextButton")
local Frame = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local slippyrb = Instance.new("TextButton")
local rbbanana = Instance.new("TextButton")
local novapag = Instance.new("TextButton")
local dupegummyrb = Instance.new("TextButton")
local Frame_3 = Instance.new("Frame")
local TextLabel_5 = Instance.new("TextLabel")
local tp1 = Instance.new("TextButton")
local tp2 = Instance.new("TextButton")
local tp3 = Instance.new("TextButton")
local tp4 = Instance.new("TextButton")
local THEBANANA = Instance.new("TextButton")
local Ben_2 = Instance.new("TextButton")
local Gummy = Instance.new("TextButton")
local poprb = Instance.new("TextButton")
local dupebabynoob = Instance.new("TextButton")
local X = Instance.new("TextButton")
local openframe = Instance.new("Frame")
local openbutton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.Active = true
MainFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BorderColor3 = Color3.fromRGB(27, 42, 53)
MainFrame.Position = UDim2.new(0.246189937, 0, 0.127063394, 0)
MainFrame.Size = UDim2.new(0, 587, 0, 380)
MainFrame.Visible = false
MainFrame.Draggable = true

thebananadupe.Name = "the banana dupe"
thebananadupe.Parent = MainFrame
thebananadupe.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
thebananadupe.BorderColor3 = Color3.fromRGB(27, 42, 53)
thebananadupe.Position = UDim2.new(-0.00158625189, 0, 0.819461584, 0)
thebananadupe.Size = UDim2.new(0, 153, 0, 57)
thebananadupe.Font = Enum.Font.SourceSans
thebananadupe.Text = "Duplicar The banana"
thebananadupe.TextColor3 = Color3.fromRGB(255, 255, 255)
thebananadupe.TextSize = 14.000
thebananadupe.MouseButton1Down:connect(function()
	local args = {
		[1] = "The banana"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "The banana" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



Momeh.Name = "Momeh"
Momeh.Parent = MainFrame
Momeh.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
Momeh.BorderColor3 = Color3.fromRGB(27, 42, 53)
Momeh.Position = UDim2.new(0.661408424, 0, 0.483070105, 0)
Momeh.Size = UDim2.new(0, 83, 0, 58)
Momeh.Font = Enum.Font.SourceSans
Momeh.Text = "momeh"
Momeh.TextColor3 = Color3.fromRGB(255, 255, 255)
Momeh.TextSize = 14.000
Momeh.MouseButton1Down:connect(function()
	local args = {
		[1] = "Mommeh Long Legs"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



Ben.Name = "Ben"
Ben.Parent = MainFrame
Ben.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
Ben.BorderColor3 = Color3.fromRGB(27, 42, 53)
Ben.Position = UDim2.new(0.664395213, 0, 0.681846857, 0)
Ben.Size = UDim2.new(0, 80, 0, 45)
Ben.Font = Enum.Font.SourceSans
Ben.Text = "Ben"
Ben.TextColor3 = Color3.fromRGB(255, 255, 255)
Ben.TextSize = 14.000
Ben.MouseButton1Down:connect(function()
	local args = {
		[1] = "Trading Ben"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



Munehh.Name = "Munehh"
Munehh.Parent = MainFrame
Munehh.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
Munehh.BorderColor3 = Color3.fromRGB(27, 42, 53)
Munehh.Position = UDim2.new(0.662914932, 0, 0.296525776, 0)
Munehh.Size = UDim2.new(0, 83, 0, 56)
Munehh.Font = Enum.Font.SourceSans
Munehh.Text = "munehh"
Munehh.TextColor3 = Color3.fromRGB(255, 255, 255)
Munehh.TextSize = 14.000
Munehh.MouseButton1Down:connect(function()
	local args = {
		[1] = "Munneh"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



TextLabel.Parent = MainFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
TextLabel.BorderColor3 = Color3.fromRGB(70, 70, 70)
TextLabel.Position = UDim2.new(0.00170357747, 0, -0.00252570538, 0)
TextLabel.Size = UDim2.new(0, 586, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "criado por shadow"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

dupepop.Name = "dupe pop"
dupepop.Parent = MainFrame
dupepop.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
dupepop.BorderColor3 = Color3.fromRGB(27, 42, 53)
dupepop.Position = UDim2.new(-0.00158625189, 0, 0.645149648, 0)
dupepop.Size = UDim2.new(0, 153, 0, 57)
dupepop.Font = Enum.Font.SourceSans
dupepop.Text = "Duplicar pop it rb"
dupepop.TextColor3 = Color3.fromRGB(255, 255, 255)
dupepop.TextSize = 14.000
dupepop.MouseButton1Down:connect(function()
	local args = {
		[1] = "Pop It Rainbow!"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "Pop It Rainbow!" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)


dupeamogusrb.Name = "dupe amogus rb"
dupeamogusrb.Parent = MainFrame
dupeamogusrb.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
dupeamogusrb.BorderColor3 = Color3.fromRGB(27, 42, 53)
dupeamogusrb.Position = UDim2.new(-0.00158625189, 0, 0.467779666, 0)
dupeamogusrb.Size = UDim2.new(0, 153, 0, 57)
dupeamogusrb.Font = Enum.Font.SourceSans
dupeamogusrb.Text = "duplicar amogus rb"
dupeamogusrb.TextColor3 = Color3.fromRGB(255, 255, 255)
dupeamogusrb.TextSize = 14.000
dupeamogusrb.MouseButton1Down:connect(function()
	local args = {
		[1] = "Amogus Rainbow"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "Amogus Rainbow" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)


dupeloly.Name = "dupe loly"
dupeloly.Parent = MainFrame
dupeloly.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
dupeloly.BorderColor3 = Color3.fromRGB(27, 42, 53)
dupeloly.Position = UDim2.new(-0.00158629019, 0, 0.149736777, 0)
dupeloly.Size = UDim2.new(0, 153, 0, 55)
dupeloly.Font = Enum.Font.SourceSans
dupeloly.Text = "Duplicar loly rb"
dupeloly.TextColor3 = Color3.fromRGB(255, 255, 255)
dupeloly.TextSize = 14.000
dupeloly.MouseButton1Down:connect(function()
	local args = {
		[1] = "Lolly Rainbow"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "Lolly Rainbow" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



dupethe.Name = "dupe the"
dupethe.Parent = MainFrame
dupethe.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
dupethe.BorderColor3 = Color3.fromRGB(27, 42, 53)
dupethe.Position = UDim2.new(-0.00328981574, 0, 0.317932516, 0)
dupethe.Size = UDim2.new(0, 153, 0, 49)
dupethe.Font = Enum.Font.SourceSans
dupethe.Text = "Duplicar crystal rb"
dupethe.TextColor3 = Color3.fromRGB(255, 255, 255)
dupethe.TextSize = 14.000
dupethe.MouseButton1Down:connect(function()
	local args = {
		[1] = "The banana"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "The banana" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)





Frame.Parent = MainFrame
Frame.BackgroundColor3 = Color3.fromRGB(176, 5, 0)
Frame.Position = UDim2.new(0.449744463, 0, 0.15080598, 0)
Frame.Size = UDim2.new(0, 10, 0, 311)

TextLabel_2.Parent = MainFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
TextLabel_2.BorderColor3 = Color3.fromRGB(70, 70, 70)
TextLabel_2.Position = UDim2.new(0.258943796, 0, 0.150806025, 0)
TextLabel_2.Size = UDim2.new(0, 111, 0, 33)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Dupe"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Frame_2.Parent = MainFrame
Frame_2.BackgroundColor3 = Color3.fromRGB(176, 5, 0)
Frame_2.Position = UDim2.new(0.647359431, 0, 0.12642163, 0)
Frame_2.Size = UDim2.new(0, 8, 0, 320)

TextLabel_3.Parent = MainFrame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
TextLabel_3.BorderColor3 = Color3.fromRGB(70, 70, 70)
TextLabel_3.Position = UDim2.new(0.662691653, 0, 0.136296123, 0)
TextLabel_3.Size = UDim2.new(0, 81, 0, 37)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Nft"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = MainFrame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
TextLabel_4.BorderColor3 = Color3.fromRGB(70, 70, 70)
TextLabel_4.Position = UDim2.new(0.466780245, 0, 0.147747919, 0)
TextLabel_4.Size = UDim2.new(0, 105, 0, 33)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Buy"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

slippyrb.Name = " slippy rb"
slippyrb.Parent = MainFrame
slippyrb.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
slippyrb.BorderColor3 = Color3.fromRGB(27, 42, 53)
slippyrb.Position = UDim2.new(0.264171869, 0, 0.244465604, 0)
slippyrb.Size = UDim2.new(0, 108, 0, 49)
slippyrb.Font = Enum.Font.SourceSans
slippyrb.Text = "slippy rb"
slippyrb.TextColor3 = Color3.fromRGB(255, 255, 255)
slippyrb.TextSize = 14.000
slippyrb.MouseButton1Down:connect(function()
	local args = {
		[1] = "Slippy Rainbow"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "Slippy Rainbow" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



rbbanana.Name = "rb banana"
rbbanana.Parent = MainFrame
rbbanana.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
rbbanana.BorderColor3 = Color3.fromRGB(27, 42, 53)
rbbanana.Position = UDim2.new(0.260764688, 0, 0.399929941, 0)
rbbanana.Size = UDim2.new(0, 112, 0, 49)
rbbanana.Font = Enum.Font.SourceSans
rbbanana.Text = "Rb banana"
rbbanana.TextColor3 = Color3.fromRGB(255, 255, 255)
rbbanana.TextSize = 14.000
rbbanana.MouseButton1Down:connect(function()
	local args = {
		[1] = "Rainbow Banana"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "Rainbow Banana" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)



novapag.Name = "nova pag"
novapag.Parent = MainFrame
novapag.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
novapag.BorderColor3 = Color3.fromRGB(27, 42, 53)
novapag.Position = UDim2.new(0.313681632, 0, 0.91315788, 0)
novapag.Size = UDim2.new(0, 53, 0, 33)
novapag.Font = Enum.Font.SourceSans
novapag.Text = "nova pagina "
novapag.TextColor3 = Color3.fromRGB(255, 255, 255)
novapag.TextSize = 14.000

dupegummyrb.Name = "dupe gummy rb"
dupegummyrb.Parent = MainFrame
dupegummyrb.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
dupegummyrb.BorderColor3 = Color3.fromRGB(27, 42, 53)
dupegummyrb.Position = UDim2.new(0.262468278, 0, 0.569606423, 0)
dupegummyrb.Size = UDim2.new(0, 109, 0, 49)
dupegummyrb.Font = Enum.Font.SourceSans
dupegummyrb.Text = "gummy rb"
dupegummyrb.TextColor3 = Color3.fromRGB(255, 255, 255)
dupegummyrb.TextSize = 14.000
dupegummyrb.MouseButton1Down:connect(function()
	local args = {
		[1] = "Gummy Rainbow"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "Gummy Rainbow" 
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)


Frame_3.Parent = MainFrame
Frame_3.BackgroundColor3 = Color3.fromRGB(176, 5, 0)
Frame_3.Position = UDim2.new(0.800681412, 0, 0.136296123, 0)
Frame_3.Size = UDim2.new(0, 5, 0, 316)

TextLabel_5.Parent = MainFrame
TextLabel_5.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
TextLabel_5.BorderColor3 = Color3.fromRGB(70, 70, 70)
TextLabel_5.Position = UDim2.new(0.809199333, 0, 0.159980327, 0)
TextLabel_5.Size = UDim2.new(0, 112, 0, 33)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "tp"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

tp1.Name = "tp1"
tp1.Parent = MainFrame
tp1.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
tp1.BorderColor3 = Color3.fromRGB(27, 42, 53)
tp1.Position = UDim2.new(0.810902894, 0, 0.272060961, 0)
tp1.Size = UDim2.new(0, 111, 0, 49)
tp1.Font = Enum.Font.SourceSans
tp1.Text = "tp"
tp1.TextColor3 = Color3.fromRGB(255, 255, 255)
tp1.TextSize = 14.000
tp1.MouseButton1Down:connect(function()
	Section:NewLabel("Teleport to Platfrom")
	Section:NewButton("Platform 1", "ButtonInfo", function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(221.47657775878906, 26.799846649169922, -208.41799926757812))
	end)



tp2.Name = "tp2"
tp2.Parent = MainFrame
tp2.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
tp2.BorderColor3 = Color3.fromRGB(27, 42, 53)
tp2.Position = UDim2.new(0.809316635, 0, 0.441536278, 0)
tp2.Size = UDim2.new(0, 112, 0, 49)
tp2.Font = Enum.Font.SourceSans
tp2.Text = "tp2"
tp2.TextColor3 = Color3.fromRGB(255, 255, 255)
tp2.TextSize = 14.000
tp2.MouseButton1Down:connect(function()
		Section:NewLabel("Teleport to Platfrom")
		Section:NewButton("Platform 2", "ButtonInfo", function()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(221.47657775878906, 26.799846649169922, -208.41799926757812))
		end)

tp3.Name = "tp3"
tp3.Parent = MainFrame
tp3.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
tp3.BorderColor3 = Color3.fromRGB(27, 42, 53)
tp3.Position = UDim2.new(0.810902894, 0, 0.675730765, 0)
tp3.Size = UDim2.new(0, 111, 0, 49)
tp3.Font = Enum.Font.SourceSans
tp3.Text = "tp3"
tp3.TextColor3 = Color3.fromRGB(255, 255, 255)
tp3.TextSize = 14.000
tp3.MouseButton1Down:connect(function()
			Section:NewLabel("Teleport to Platfrom")
			Section:NewButton("Platform 3", "ButtonInfo", function()
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(221.47657775878906, 26.799846649169922, -208.41799926757812))
			end)

tp4.Name = "tp4"
tp4.Parent = MainFrame
tp4.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
tp4.BorderColor3 = Color3.fromRGB(27, 42, 53)
tp4.Position = UDim2.new(0.810902894, 0, 0.828362346, 0)
tp4.Size = UDim2.new(0, 111, 0, 49)
tp4.Font = Enum.Font.SourceSans
tp4.Text = "tp4"
tp4.TextColor3 = Color3.fromRGB(255, 255, 255)
tp4.TextSize = 14.000			
tp4.MouseButton1Down:connect(function()		
				Section:NewLabel("Teleport to Platfrom")
				Section:NewButton("Platform 4", "ButtonInfo", function()
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(221.47657775878906, 26.799846649169922, -208.41799926757812))
				end)				
				
				
THEBANANA.Name = "THE BANANA"
THEBANANA.Parent = MainFrame
THEBANANA.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
THEBANANA.BorderColor3 = Color3.fromRGB(27, 42, 53)
THEBANANA.Position = UDim2.new(0.465299994, 0, 0.246525779, 0)
THEBANANA.Size = UDim2.new(0, 106, 0, 56)
THEBANANA.Font = Enum.Font.SourceSans
THEBANANA.Text = "The banana"
THEBANANA.TextColor3 = Color3.fromRGB(255, 255, 255)
THEBANANA.TextSize = 14.000
THEBANANA.MouseButton1Down:connect(function()
	Scripthere
end)


Ben_2.Name = "Ben"
Ben_2.Parent = MainFrame
Ben_2.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
Ben_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
Ben_2.Position = UDim2.new(0.465299994, 0, 0.414946824, 0)
Ben_2.Size = UDim2.new(0, 106, 0, 56)
Ben_2.Font = Enum.Font.SourceSans
Ben_2.Text = "Ben"
Ben_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Ben_2.TextSize = 14.000
Ben_2.MouseButton1Down:connect(function()
	Scripthere
end)


Gummy.Name = "Gummy"
Gummy.Parent = MainFrame
Gummy.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
Gummy.BorderColor3 = Color3.fromRGB(27, 42, 53)
Gummy.Position = UDim2.new(0.465299994, 0, 0.588631094, 0)
Gummy.Size = UDim2.new(0, 106, 0, 56)
Gummy.Font = Enum.Font.SourceSans
Gummy.Text = "Gummy"
Gummy.TextColor3 = Color3.fromRGB(255, 255, 255)
Gummy.TextSize = 14.000
Gummy.MouseButton1Down:connect(function()
	Scripthere
end)


poprb.Name = "pop rb"
poprb.Parent = MainFrame
poprb.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
poprb.BorderColor3 = Color3.fromRGB(27, 42, 53)
poprb.Position = UDim2.new(0.470410734, 0, 0.793894172, 0)
poprb.Size = UDim2.new(0, 100, 0, 56)
poprb.Font = Enum.Font.SourceSans
poprb.Text = "pop it rb"
poprb.TextColor3 = Color3.fromRGB(255, 255, 255)
poprb.TextSize = 14.000
poprb.MouseButton1Down:connect(function()
	Scripthere
end)


dupebabynoob.Name = "dupe baby noob"
dupebabynoob.Parent = MainFrame
dupebabynoob.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
dupebabynoob.BorderColor3 = Color3.fromRGB(27, 42, 53)
dupebabynoob.Position = UDim2.new(0.265875429, 0, 0.735395908, 0)
dupebabynoob.Size = UDim2.new(0, 109, 0, 49)
dupebabynoob.Font = Enum.Font.SourceSans
dupebabynoob.Text = "Baby noob"
dupebabynoob.TextColor3 = Color3.fromRGB(255, 255, 255)
dupebabynoob.TextSize = 14.000
dupebabynoob.MouseButton1Down:connect(function()
	
end)


X.Name = "X"
X.Parent = MainFrame
X.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
X.BorderColor3 = Color3.fromRGB(27, 42, 53)
X.Position = UDim2.new(0.940374732, 0, 0.00289949309, 0)
X.Size = UDim2.new(0, 35, 0, 45)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 255, 255)
X.TextSize = 14.000
X.MouseButton1Down:connect(function()
	openframe.Visible = true
	MainFrame.Visible = false
end)

openframe.Name = "open frame"
openframe.Parent = ScreenGui
openframe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
openframe.Position = UDim2.new(0.00820632838, 0, 0.645654917, 0)
openframe.Size = UDim2.new(0, 155, 0, 34)

openbutton.Name = "open button"
openbutton.Parent = openframe
openbutton.BackgroundColor3 = Color3.fromRGB(168, 18, 18)
openbutton.BorderColor3 = Color3.fromRGB(27, 42, 53)
openbutton.Position = UDim2.new(-0.0451612771, 0, 0, 0)
openbutton.Size = UDim2.new(0, 163, 0, 33)
openbutton.Font = Enum.Font.SourceSans
openbutton.Text = "Open"
openbutton.TextColor3 = Color3.fromRGB(255, 255, 255)
openbutton.TextSize = 14.000
openbutton.MouseButton1Down:connect(function()
	MainFrame.Visible = true
	openframe.Visible = false
end)
