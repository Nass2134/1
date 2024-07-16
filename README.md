local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "(HOOPS DEMO) HAXHUB ",
   LoadingTitle = "HAXHUB Paid Edition.",
   LoadingSubtitle = "by HaxNas",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = hax, -- Create a custom folder for your hub/game
      FileName = "hax hub"
   },
   Discord = {
      Enabled = true,
      Invite = "discord.gg/haxscripts", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "HAXHUB Key System",
      Subtitle = "Need Key!",
      Note = "Purchase From Discord!",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"pkwDDWKadanopNODNWAOP", "hcnDSIJCns"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})



local Tab = Window:CreateTab("MAIN", 4483362458) -- Title, Image


local Section = Tab:CreateSection("AutoGreen")



local Button = Tab:CreateButton({
   Name = "AutoGreen (R)",
   Callback = function()
   local function ShotMeter()
	local Aimbot1 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["200"]
	Aimbot1:Destroy()
	local Aimbot2 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["199"]
	Aimbot2:Destroy()
	local Aimbot3 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["198"]
	Aimbot3:Destroy()
	local Aimbot4 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["197"]
	Aimbot4:Destroy()
	local Aimbot5 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["196"]
	Aimbot5:Destroy()
	local Aimbot6 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["195"]
	Aimbot6:Destroy()
	local Aimbot7 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["194"]
	Aimbot7:Destroy()
	local Aimbot8 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["193"]
	Aimbot8:Destroy()
	local Aimbot9 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["192"]
	Aimbot9:Destroy()
	local Aimbot10 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["191"]
	Aimbot10:Destroy()
	local Aimbot11 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["190"]
	Aimbot11:Destroy()
	local Aimbot12 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["189"]
	Aimbot12:Destroy()
	local Aimbot13 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["187"]
	Aimbot13:Destroy()
	local Aimbot14 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["188"]
	Aimbot14:Destroy()
	local Aimbot15 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["186"]
	Aimbot15:Destroy()
	local Aimbot16 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["185"]
	Aimbot16:Destroy()
	local Aimbot17 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["184"]
	Aimbot17:Destroy()
	local Aimbot18 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["183"]
	Aimbot18:Destroy()
	local Aimbot19 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["182"]
	Aimbot19:Destroy()
	local Aimbot20 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["181"]
	Aimbot20:Destroy()
	local Aimbot21 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["180"] 
	Aimbot21:Destroy()
	local Aimbot22 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["179"]
	Aimbot22:Destroy()
	local Aimbot23 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["178"]
	Aimbot23:Destroy()
	local Aimbot24 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["177"]
	Aimbot24:Destroy()
	local Aimbot24 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["176"]
	Aimbot24:Destroy()
	local Aimbot25 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["175"]
	Aimbot25:Destroy()
	local Aimbot26 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["174"]
	Aimbot26:Destroy()
	local Aimbot27 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["173"]
	Aimbot27:Destroy()
	local Aimbot28 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["172"]
	Aimbot28:Destroy()
	local Aimbot29 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["171"]
	Aimbot29:Destroy()
	local Aimbot30 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["170"]
	Aimbot30:Destroy()
	local Aimbot31 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["169"]
	Aimbot31:Destroy()
	local Aimbot32 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["168"]
	Aimbot32:Destroy()
	local Aimbot33 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["167"]
	Aimbot33:Destroy()
	local Aimbot34 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["166"]
	Aimbot34:Destroy()
	local Aimbot35 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["165"]
	Aimbot35:Destroy()
	local Aimbot36 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["164"]
	Aimbot36:Destroy()
	local Aimbot37 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["163"]
	Aimbot37:Destroy()
	local Aimbot38 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["162"]
	Aimbot38:Destroy()
	local Aimbot39 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["161"]
	Aimbot39:Destroy()
	local Aimbot40 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["160"]
	Aimbot40:Destroy()
	local Aimbot41 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["159"]
	Aimbot41:Destroy()
	local Aimbot42 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["158"]
	Aimbot42:Destroy()
	local Aimbot43 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["157"]
	Aimbot43:Destroy()
	local Aimbot44 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["156"]
	Aimbot44:Destroy()
	local Aimbot45 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["155"]
	Aimbot45:Destroy()
	local Aimbot46 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["154"]
	Aimbot46:Destroy()
	local Aimbot47 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["153"]
	Aimbot47:Destroy()
	local Aimbot48 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["152"]
	Aimbot48:Destroy()
	local Aimbot49 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["151"]
	Aimbot49:Destroy()
	local Aimbot50 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["150"]
	Aimbot50:Destroy()
	local Aimbot51 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["149"]
	Aimbot51:Destroy()
	local Aimbot52 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["148"]
	Aimbot52:Destroy()
	local Aimbot53 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["147"]
	Aimbot53:Destroy()
	local Aimbot54 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["146"]
	Aimbot54:Destroy()
	local Aimbot55 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["145"]
	Aimbot55:Destroy()
	local Aimbot56 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["144"]
	Aimbot56:Destroy()
	local Aimbot57 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["143"]
	Aimbot57:Destroy()
	local Aimbot58 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["142"]
	Aimbot58:Destroy()
	local Aimbot59 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["141"]
	Aimbot59:Destroy()
	local Aimbot60 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["140"]
	Aimbot60:Destroy()
	local Aimbot61 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["139"]
	Aimbot61:Destroy()
	local Aimbot62 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["138"]
	Aimbot62:Destroy()
	local Aimbot63 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["137"]
	Aimbot63:Destroy()
	local Aimbot64 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["136"]
	Aimbot64:Destroy()
	local Aimbot65 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["135"]
	Aimbot65:Destroy()
	local Aimbot66 = game.ReplicatedStorage.ShotMeter.SurfaceGui.Circle["134"]
	Aimbot66:Destroy()

	

	
end

ShotMeter()

   end,
})

local Button = Tab:CreateButton({
   Name = "INF STAMINA",
   Callback = function()
   while true do
game.Players.LocalPlayer.PlayerScripts.Events.Player.Stamina.Stamina.Value = 9001
wait()
end
   end,
})




local Section = Tab:CreateSection("Other HAXHUB ")

local Button = Tab:CreateButton({
   Name = "HAXHUB Gui",
   Callback = function()
    --Script Created by Created Ren Gui Made by Juan
--To Use aimbot click aimbot and Hold The Shoot button until it shoots for you Make sure to take a shot at a Close/Semi-Far Area for it to work
 
local FGTJQWIKGDRUJEIQAJSDXFUGIK = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local test = Instance.new("TextButton")
local test2 = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
--Encrypted Name (PLEASE IGNORE ):
FGTJQWIKGDRUJEIQAJSDXFUGIK.Name = "FGTJQWIKGDRUJEIQAJSDXFUGIK"
FGTJQWIKGDRUJEIQAJSDXFUGIK.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
 
Frame.Parent = FGTJQWIKGDRUJEIQAJSDXFUGIK
Frame.BackgroundColor3 = Color3.new(1, 1, 1)
Frame.Position = UDim2.new(0.490139693, -375, 0.514742017, -260)
Frame.Size = UDim2.new(0, 750, 0, 260)
Frame.Visible = false
Frame.Style = Enum.FrameStyle.DropShadow
 
TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel.BackgroundTransparency = 0.63999998569489
TextLabel.Size = UDim2.new(1, 0, 0, 60)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Youtube:HaxNas"
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextScaled = true
TextLabel.TextSize = 60
TextLabel.TextWrapped = true
 
test.Name = "test"
test.Parent = Frame
test.BackgroundColor3 = Color3.new(1, 1, 1)
test.Position = UDim2.new(0.286929786, 0, 0.316183418, 0)
test.Size = UDim2.new(0, 312, 0, 50)
test.Font = Enum.Font.SourceSans
test.Text = "Infinite Stamina"
test.TextColor3 = Color3.new(0, 0, 0)
test.TextSize = 29
test.MouseButton1Click:connect(function()
    while true do
game.Players.LocalPlayer.PlayerScripts.Events.Player.Stamina.Stamina.Value = 9001
wait()
end
end)
 
 
 
test2.Name = "test2"
test2.Parent = Frame
test2.BackgroundColor3 = Color3.new(1, 1, 1)
test2.Position = UDim2.new(0.286929786, 0, 0.560414195, 0)
test2.Size = UDim2.new(0, 312, 0, 50)
test2.Font = Enum.Font.SourceSans
test2.Text = "Aimbot"
test2.TextColor3 = Color3.new(0, 0, 0)
test2.TextSize = 29
test2.MouseButton1Click:connect(function()
        function onKeyPress(inputObject, gameProcessedEvent)
if inputObject.KeyCode == Enum.KeyCode.R then
game.ReplicatedStorage.Ball.StartShooting:FireServer()
        wait(0.5)
        game.ReplicatedStorage.Ball.EndShooting:InvokeServer(true,"Perfect")
end
end
 
game:GetService("UserInputService").InputBegan:connect(onKeyPress)
end)
 
 
 
TextButton.Parent = FGTJQWIKGDRUJEIQAJSDXFUGIK
TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton.BorderColor3 = Color3.new(0.101961, 0.290196, 0.0901961)
TextButton.Position = UDim2.new(0, 0, 0.5, 200)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "HAX HUB"
TextButton.TextSize = 20
 
-- Scripts:
function SCRIPT_LUAN71_FAKESCRIPT() 
    local script = Instance.new('LocalScript')
    script.Parent = TextLabel
    while wait() do
        script.Parent.TextColor3 = Color3.new(1,0,0)
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g+(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r-(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b+(17/255))
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g-(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r+(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b-(17/255))
        end
    end
 
end
coroutine.resume(coroutine.create(SCRIPT_LUAN71_FAKESCRIPT))
function SCRIPT_UHLU74_FAKESCRIPT() -- Basic Rainbow Script 
    local script = Instance.new('LocalScript')
    script.Parent = test
    while wait() do
        script.Parent.TextColor3 = Color3.new(1,0,0)
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g+(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r-(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b+(17/255))
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g-(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r+(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b-(17/255))
        end
    end
 
end
coroutine.resume(coroutine.create(SCRIPT_UHLU74_FAKESCRIPT))
function SCRIPT_GNSJ86_FAKESCRIPT() -- Basic Rainbow Script
    local script = Instance.new('LocalScript')
    script.Parent = test2
    while wait() do
        script.Parent.TextColor3 = Color3.new(1,0,0)
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g+(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r-(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b+(17/255))
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g-(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r+(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b-(17/255))
        end
    end
 
end
coroutine.resume(coroutine.create(SCRIPT_GNSJ86_FAKESCRIPT))
function SCRIPT_PFWO87_FAKESCRIPT() -- TextButton.LocalScript 
    local script = Instance.new('LocalScript')
    script.Parent = TextButton
    local box = script.Parent.Parent.Frame 
    local plr = game.Players.LocalPlayer
    local open = false
    
    script.Parent.MouseButton1Click:connect(function()
        if open == false then
            box.Visible = true
            open = true
        elseif open == true then
            box.Visible = false
            open = false
        
        end
        
        
    end)
 
end
coroutine.resume(coroutine.create(SCRIPT_PFWO87_FAKESCRIPT))
function SCRIPT_USXA69_FAKESCRIPT() -- Basic Rainbow Script
    local script = Instance.new('LocalScript')
    script.Parent = TextButton
    while wait() do
        script.Parent.TextColor3 = Color3.new(1,0,0)
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g+(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r-(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b+(17/255))
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g-(17/255),script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r+(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
        end
        for i=1,15 do
            game:GetService("RunService").RenderStepped:wait()
            script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b-(17/255))
        end
    end
 
end
coroutine.resume(coroutine.create(SCRIPT_USXA69_FAKESCRIPT))
   end,
})


local Section = Tab:CreateSection("Dunk Script")

local Button = Tab:CreateButton({
   Name = "Dunk Script (LEFT SIDE HOOP)",
   Callback = function()
   -- Floor > RightSide > Stand > Hoop > GoalDetection
--Important Things--

local plr = game.Players.LocalPlayer
local UIS = game:GetService("UserInputService")
local testingDeb = false
local ball = game.Workspace.Basketball

--ONLY MODIFY THESE--

local finalForce = Vector3.new(0, 10, 10)--10 For normal 360, 20 for cocked out one
local key = Enum.KeyCode.Space
local side = "Left"
local waitTime = .15--.15 for normal 360

--Key Detection Things--

UIS.InputBegan:Connect(function(input, GPE)
    --if(not GPE) then
    if(input.KeyCode == key) then
        if(testingDeb == true) then return end
        local BAV = Instance.new("BodyAngularVelocity")
        BAV.Parent = plr.Character.HumanoidRootPart
        BAV.MaxTorque = Vector3.new(40000, 40000000, 40000)
        BAV.AngularVelocity = finalForce
        wait(.65)
        BAV:Destroy()
        testingDeb = true
        wait(0.025)
        local BP = Instance.new("BodyPosition")
        BP.P = 2000
        BP.MaxForce = Vector3.new(9999, 9999, 9999)
        BP.Parent = ball
        BP.Position = game.Workspace.Floor[side.."Side"].Stand.Hoop.ActualRim.Position
        wait(waitTime)
        BP:Destroy()
        --game.Workspace.basketball.Position = Floor[side.."Side"].Stand.Hoop.Rim.Position
       end
    --end
end)
   end,
})



local Section = Tab:CreateSection("Dunk Power Script")


local Button = Tab:CreateButton({
   Name = "Dunk Power!",
   Callback = function()
   local strength = 1000000000000000000000000000000000000 --put what strength you want here
local Plr = game.Players.LocalPlayer
if Plr.Character then
local descs = Plr.Character:GetDescendants()
for i = 1, #descs do
local desc = descs[i]
if desc:IsA"BasePart"then
desc.CustomPhysicalProperties = PhysicalProperties.new(100, 0.3, 0.5)
end
end
end
   end,
})




local Section = Tab:CreateSection("Extra")


local Slider = Tab:CreateSlider({
   Name = "HipHeight (NoContest)",
   Range = {2, 20},
   Increment = 1,
   Suffix = "Float",
   CurrentValue = 0,
   Flag = "Slider2", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(c)
   game.Players.LocalPlayer.Character.Humanoid.HipHeight = c
   end,
})








local Slider = Tab:CreateSlider({
   Name = "Walkspeed",
   Range = {16, 100},
   Increment = 5,
   Suffix = "RAGE WalkSpeed",
   CurrentValue = 0,
   Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(V)
   game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = V
   end,
})
