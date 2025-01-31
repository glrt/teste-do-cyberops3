-- Gui to Lua
-- Version: 3.2

-- Instances:

local Menu = Instance.new("ScreenGui")
local aba = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Fechar = Instance.new("TextButton")
local Minimizar = Instance.new("TextButton")
local Fundohub = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Nomedohub = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local Infiniteyield = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local Byglr = Instance.new("TextLabel")
local bang = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local scp096 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local invisible = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")

--Properties:

Menu.Name = "Menu"
Menu.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Menu.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

aba.Name = "aba"
aba.Parent = Menu
aba.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
aba.BorderColor3 = Color3.fromRGB(0, 0, 0)
aba.BorderSizePixel = 0
aba.Position = UDim2.new(0.270105064, 0, 0.275811136, 0)
aba.Size = UDim2.new(0, 414, 0, 35)

UICorner.Parent = aba

Fechar.Name = "Fechar"
Fechar.Parent = aba
Fechar.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Fechar.BorderColor3 = Color3.fromRGB(0, 0, 0)
Fechar.BorderSizePixel = 0
Fechar.Position = UDim2.new(0.914006293, 0, 0, 0)
Fechar.Size = UDim2.new(0, 30, 0, 24)
Fechar.Font = Enum.Font.SourceSans
Fechar.Text = "X"
Fechar.TextColor3 = Color3.fromRGB(255, 11, 3)
Fechar.TextScaled = true
Fechar.TextSize = 14.000
Fechar.TextWrapped = true
Fechar.MouseButton1Down:Connect(function()
	Menu:Destroy()
end)

Minimizar.Name = "Minimizar"
Minimizar.Parent = aba
Minimizar.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Minimizar.BorderColor3 = Color3.fromRGB(0, 0, 0)
Minimizar.BorderSizePixel = 0
Minimizar.Position = UDim2.new(0.000753306202, 0, 0, 0)
Minimizar.Size = UDim2.new(0, 38, 0, 24)
Minimizar.Font = Enum.Font.SourceSans
Minimizar.Text = "-"
Minimizar.TextColor3 = Color3.fromRGB(93, 142, 255)
Minimizar.TextScaled = true
Minimizar.TextSize = 14.000
Minimizar.TextWrapped = true
Minimizar.MouseButton1Down:Connect(function()

end)

Fundohub.Name = "Fundo hub"
Fundohub.Parent = aba
Fundohub.BackgroundColor3 = Color3.fromRGB(33, 32, 32)
Fundohub.BorderColor3 = Color3.fromRGB(0, 0, 0)
Fundohub.BorderSizePixel = 0
Fundohub.Position = UDim2.new(-0.00292157894, 0, 0.683832228, 0)
Fundohub.Size = UDim2.new(0, 415, 0, 282)

UICorner_2.Parent = Fundohub

Nomedohub.Name = "Nome do hub"
Nomedohub.Parent = Fundohub
Nomedohub.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
Nomedohub.BorderColor3 = Color3.fromRGB(0, 0, 0)
Nomedohub.BorderSizePixel = 0
Nomedohub.Position = UDim2.new(0.000158912022, 0, 0, 0)
Nomedohub.Size = UDim2.new(0, 202, 0, 62)
Nomedohub.Font = Enum.Font.FredokaOne
Nomedohub.Text = "Cyber Ops Hub"
Nomedohub.TextColor3 = Color3.fromRGB(255, 255, 255)
Nomedohub.TextSize = 20.000
Nomedohub.TextWrapped = true

UICorner_3.Parent = Nomedohub

Infiniteyield.Name = "Infinite yield"
Infiniteyield.Parent = Fundohub
Infiniteyield.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
Infiniteyield.BorderColor3 = Color3.fromRGB(0, 0, 0)
Infiniteyield.BorderSizePixel = 0
Infiniteyield.Position = UDim2.new(0.489156634, 0, 0.276595742, 0)
Infiniteyield.Size = UDim2.new(0, 183, 0, 42)
Infiniteyield.Font = Enum.Font.SourceSans
Infiniteyield.Text = "infinite yield"
Infiniteyield.TextColor3 = Color3.fromRGB(185, 25, 25)
Infiniteyield.TextSize = 14.000
Infiniteyield.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/edgeiy/infiniteyield/master/source'))()
end)

UICorner_4.Parent = Infiniteyield

TextLabel.Name = "--"
TextLabel.Parent = Fundohub
TextLabel.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-3.67681672e-08, 0, 0.177304968, 0)
TextLabel.Size = UDim2.new(0, 414, 0, 37)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "--------------------------------------------------------------------------------"
TextLabel.TextColor3 = Color3.fromRGB(115, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UICorner_5.Parent = TextLabel

Byglr.Name = "By glr"
Byglr.Parent = Fundohub
Byglr.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
Byglr.BorderColor3 = Color3.fromRGB(0, 0, 0)
Byglr.BorderSizePixel = 0
Byglr.Position = UDim2.new(0.800000012, 0, 0.180851057, 0)
Byglr.Size = UDim2.new(0, 77, 0, 27)
Byglr.Font = Enum.Font.Unknown
Byglr.Text = "By glr"
Byglr.TextColor3 = Color3.fromRGB(247, 0, 0)
Byglr.TextSize = 14.000
Byglr.TextWrapped = true

bang.Name = "bang"
bang.Parent = Fundohub
bang.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
bang.BorderColor3 = Color3.fromRGB(0, 0, 0)
bang.BorderSizePixel = 0
bang.Position = UDim2.new(0.0673250109, 0, 0.274569362, 0)
bang.Size = UDim2.new(0, 183, 0, 42)
bang.Font = Enum.Font.SourceSans
bang.Text = "bang"
bang.TextColor3 = Color3.fromRGB(185, 25, 25)
bang.TextSize = 14.000
bang.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://gist.githubusercontent.com/benguss/282f472a00289fc4fb8ac95a5c0a6488/raw/23a402a19a7bdead6080dfe36498b68d0c3de779/Roblox%2520Bang%2520Script%2520(NSFW)'))()
end)

UICorner_6.Parent = bang

scp096.Name = "scp096"
scp096.Parent = Fundohub
scp096.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
scp096.BorderColor3 = Color3.fromRGB(0, 0, 0)
scp096.BorderSizePixel = 0
scp096.Position = UDim2.new(0.0673250109, 0, 0.423505515, 0)
scp096.Size = UDim2.new(0, 183, 0, 42)
scp096.Font = Enum.Font.SourceSans
scp096.Text = "FE Scp 096"
scp096.TextColor3 = Color3.fromRGB(185, 25, 25)
scp096.TextSize = 14.000
scp096.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/glrt/fe-scp096/refs/heads/main/fescp096.lua'))()'))()
end)

UICorner_7.Parent = scp096

invisible.Name = "invisible"
invisible.Parent = Fundohub
invisible.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
invisible.BorderColor3 = Color3.fromRGB(0, 0, 0)
invisible.BorderSizePixel = 0
invisible.Position = UDim2.new(0.489011675, 0, 0.448328227, 0)
invisible.Size = UDim2.new(0, 183, 0, 42)
invisible.Font = Enum.Font.SourceSans
invisible.Text = "invisible"
invisible.TextColor3 = Color3.fromRGB(185, 25, 25)
invisible.TextSize = 14.000
invisible.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/glrt/invisible-fe/refs/heads/main/fe_invisible.lua'))()'))()'))()
end)

UICorner_8.Parent = invisible