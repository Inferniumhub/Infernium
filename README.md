--By BinaryH


-- Instances:

local VersusExploitHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local ArsenalHub = Instance.new("TextButton")
local Alinity_Hub = Instance.new("TextButton")

--Properties:

VersusExploitHub.Name = "VersusExploitHub"
VersusExploitHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = VersusExploitHub
Frame.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Frame.Position = UDim2.new(0.397790045, 0, 0.346420318, 0)
Frame.Size = UDim2.new(0, 310, 0, 134)
Frame.Active = true
Frame.Draggable = true

Title.Name = "Title"
Title.Parent = Frame
Title.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(-0.000831653248, 0, -0.00177717209, 0)
Title.Size = UDim2.new(0, 310, 0, 48)
Title.Font = Enum.Font.SpecialElite
Title.Text = "Versus Exploit Hub"
Title.TextColor3 = Color3.fromRGB(184, 184, 184)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextStrokeTransparency = 0.000
Title.TextWrapped = true
Title.Draggable = true

ArsenalHub.Name = "Animal_Simulator"
ArsenalHub.Parent = Frame
ArsenalHub.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
ArsenalHub.BorderSizePixel = 0
ArsenalHub.Position = UDim2.new(0.0290322565, 0, 0.514750481, 0)
ArsenalHub.Size = UDim2.new(0, 132, 0, 44)
ArsenalHub.Font = Enum.Font.SourceSans
ArsenalHub.Text = "Animal_Simulator"
ArsenalHub.TextColor3 = Color3.fromRGB(0, 0, 0)
ArsenalHub.TextScaled = true
ArsenalHub.TextSize = 14.000
ArsenalHub.TextWrapped = true
ArsenalHub.MouseButton1Click:Connect(function()

	_G.RedGUI = true
_G.Theme = "Dark" -- Must disable or remove _G.RedGUI to use
--Themes: Light, Dark, Mocha, Aqua and Jester

loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/AnimalSimulator.lua"))()
end)

Alinity_Hub.Name = "Infernium"
Alinity_Hub.Parent = Frame
Alinity_Hub.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Alinity_Hub.BorderSizePixel = 0
Alinity_Hub.Position = UDim2.new(0.541935444, 0, 0.514750481, 0)
Alinity_Hub.Size = UDim2.new(0, 132, 0, 44)
Alinity_Hub.Font = Enum.Font.SourceSans
Alinity_Hub.Text = "Infernium"
Alinity_Hub.TextColor3 = Color3.fromRGB(0, 0, 0)
Alinity_Hub.TextScaled = true
Alinity_Hub.TextSize = 14.000
Alinity_Hub.TextWrapped = true
Alinity_Hub.MouseButton1Click:Connect(function()

	loadstring(game:HttpGet("https://raw.githubusercontent.com/Kylan83728/V2/refs/heads/main/README.md"))()
end)
