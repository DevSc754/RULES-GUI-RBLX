-- LocalScript inside StarterGui > ScreenGui

-- Create ScreenGui
local screenGui = script.Parent

-- Create Frame
local frame = Instance.new("Frame")
frame.Size = UDim2.new(0, 400, 0, 300)
frame.Position = UDim2.new(0.5, -200, 0.5, -150)
frame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
frame.BorderSizePixel = 0
frame.Visible = true
frame.Parent = screenGui

-- Title
local title = Instance.new("TextLabel")
title.Size = UDim2.new(1, 0, 0, 50)
title.BackgroundTransparency = 1
title.Font = Enum.Font.SourceSansBold
title.TextSize = 28
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.Text = "Game Rules"
title.Parent = frame

-- Rules text
local rules = Instance.new("TextLabel")
rules.Size = UDim2.new(1, -20, 1, -70)
rules.Position = UDim2.new(0, 10, 0, 60)
rules.BackgroundTransparency = 1
rules.Font = Enum.Font.SourceSans
rules.TextSize = 20
rules.TextColor3 = Color3.fromRGB(255, 255, 255)
rules.TextWrapped = true
rules.TextYAlignment = Enum.TextYAlignment.Top
rules.Text = [[
1. Be respectful to other players.
2. No cheating, exploiting, or hacking.
3. No spamming in chat.
4. Follow Roblox’s community guidelines.
5. Have fun!
]]
rules.Parent = frame

-- Close button
local closeBtn = Instance.new("TextButton")
closeBtn.Size = UDim2.new(0, 100, 0, 40)
closeBtn.Position = UDim2.new(0.5, -50, 1, -50)
closeBtn.BackgroundColor3 = Color3.fromRGB(200, 0, 0)
closeBtn.Font = Enum.Font.SourceSansBold
closeBtn.TextSize = 20
closeBtn.TextColor3 = Color3.fromRGB(255, 255, 255)
closeBtn.Text = "Close"
closeBtn.Parent = frame

-- Close button function
closeBtn.MouseButton1Click:Connect(function()
	frame.Visible = false
end)
