local SytroWaterMark = Instance.new("ScreenGui")

local TextLabel = Instance.new("TextButton")

local UIGradient = Instance.new("UIGradient")

local TextLabel_2 = Instance.new("TextLabel")

local UIGradient_2 = Instance.new("UIGradient")

local UITextSizeConstraint = Instance.new("UITextSizeConstraint")

local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")

SytroWaterMark.Name = "SytroWaterMark"

SytroWaterMark.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

SytroWaterMark.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

SytroWaterMark.ResetOnSpawn = false

TextLabel.Parent = SytroWaterMark

TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

TextLabel.BackgroundTransparency = 1.000

TextLabel.BorderSizePixel = 0

TextLabel.Position = UDim2.new(-0.000772226602, 0, 0.0343558267, 0)

TextLabel.Size = UDim2.new(0.170134634, 0, 0.0700389072, 0)

TextLabel.Font = Enum.Font.GothamBold

TextLabel.Text = "Fire Hub"

TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)

TextLabel.TextScaled = true

TextLabel.TextSize = 28.000

TextLabel.TextWrapped = true

TextLabel.TextXAlignment = Enum.TextXAlignment.Left

TextLabel.MouseButton1Down:Connect(function()

end)

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(126, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(209, 0, 0))}

UIGradient.Parent = TextLabel

TextLabel_2.Parent = TextLabel

TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

TextLabel_2.BackgroundTransparency = 1.000

TextLabel_2.BorderSizePixel = 0

TextLabel_2.Position = UDim2.new(-0.000772226602, 0, 0.67410934, 0)

TextLabel_2.Size = UDim2.new(1, 0, 1, 0)

TextLabel_2.Font = Enum.Font.GothamBold

TextLabel_2.Text = "V2"

TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)

TextLabel_2.TextScaled = true

TextLabel_2.TextSize = 24.000

TextLabel_2.TextWrapped = true

TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(126, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(209, 0, 0))}

UIGradient_2.Parent = TextLabel_2

UITextSizeConstraint.Parent = TextLabel_2

UITextSizeConstraint.MaxTextSize = 24

UITextSizeConstraint_2.Parent = TextLabel

UITextSizeConstraint_2.MaxTextSize = 27

local vu = game:GetService("VirtualUser")

game:GetService("Players").LocalPlayer.Idled:connect(function()

    vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

    wait(1)

    vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

end)

wait(0.1)

game:GetService("StarterGui"):SetCore("SendNotification",{
	Title = "Fire Hub V2", -- Required
	Text = "Why? Bc I Want This Version I Dont Like V0.1/V0.2",
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150" -- Option
})

wait(0.1)

game:GetService("StarterGui"):SetCore("SendNotification",{
	Title = "Updating Fire Hub V2 To Fire Hub V3 Or V4", -- Required
	Text = "In Usa July 18 In SouthEast Asia July 19 Bc Its My Bday :D",
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150" -- Option
})

local StarterGui = game:GetService("StarterGui")
local bindable1 = Instance.new("BindableFunction")

function bindable1.OnInvoke(response)
setclipboard('https://m.youtube.com/channel/UCxfiH1VLU1H6td_ny_Bt0oQ')
end

StarterGui:SetCore("SendNotification", {
	Title = "Youtube",
	Text = "Subcribe Youtube",
	Duration = 6,
	Callback = bindable1,
	Button1 = "Sure",
})
wait(0.1)
local StarterGui = game:GetService("StarterGui")
local bindable1 = Instance.new("BindableFunction")

function bindable1.OnInvoke(response)
setclipboard('https://discord.gg/ZqaHxdsK')
end

StarterGui:SetCore("SendNotification", {
	Title = "Discord",
	Text = "Join Discord :D",
	Duration = 5,
	Callback = bindable1,
	Button1 = "Sure",
})
game:GetService("StarterGui"):SetCore("SendNotification", { 
	Title = "Fire Hub V0.2";
	Text = "By Fire alt1lr#9459";
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150"})
Duration = 3;
wait(2)
local message = Instance.new("Message",workspace) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1) 

message.Text = "Loading..." 

wait(1) 

message.Text = "Loading" 

wait(1) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1) 

message.Text = "Loading..." 

wait(1) 

message.Text = "Loading" 

wait(1) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1.8) 

message:Destroy()
local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Fire Hub [1]", "BloodTheme")

local Tab1 = Window:NewTab("Scripts")
local Tab1Section = Tab1:NewSection("Script")

local Tab2 = Window:NewTab("Natural Disaster")
local Tab2Section = Tab2:NewSection("Natural Disaster")

local Tab3 = Window:NewTab("Build The Boat")
local Tab3Section = Tab3:NewSection(" Build The Boat")

local Tab5 = Window:NewTab("Tower Of Misery")
local Tab5Section = Tab5:NewSection(" Tower Of Misery")

Tab1Section:NewToggle("Walk Or Shift", "", function(state)
    if state then
game:GetService("StarterGui"):SetCore("SendNotification", { 
	Title = "Shift On!";
	Text = "Click The Toggle To Walk";
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150"})
Duration = 3;
wait(0.1)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30
    else
game:GetService("StarterGui"):SetCore("SendNotification", { 
	Title = "Walk On!";
	Text = "Click The Toggle To Shift";
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150"})
Duration = 3;
wait(0.1)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 15
    end
end)

Tab1Section:NewToggle("Hitbox", "", function(state)
    if state then
_G.HeadSize = 25
_G.Disabled = true

game:GetService('RunService').RenderStepped:connect(function()
if _G.Disabled then
for i,v in next, game:GetService('Players'):GetPlayers() do
if v.Name ~= game:GetService('Players').LocalPlayer.Name then
pcall(function()
v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
v.Character.HumanoidRootPart.Transparency = 0.7
v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really black")
v.Character.HumanoidRootPart.Material = "Neon"
v.Character.HumanoidRootPart.CanCollide = false
end)
end
end
end
end)
    else
_G.HeadSize = 0
_G.Disabled = true

game:GetService('RunService').RenderStepped:connect(function()
if _G.Disabled then
for i,v in next, game:GetService('Players'):GetPlayers() do
if v.Name ~= game:GetService('Players').LocalPlayer.Name then
pcall(function()
v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
v.Character.HumanoidRootPart.Transparency = 0.7
v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really black")
v.Character.HumanoidRootPart.Material = "Neon"
v.Character.HumanoidRootPart.CanCollide = false
end)
end
end
end
end)
    end
end)

Tab1Section:NewToggle("Auto Jump", "", function(state)
    if state then
        while true do wait(0.000001)
game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping") 
wait(1)
end
    else
        game.Players.LocalPlayer.Character:Destroy()
    end
end)

Tab1Section:NewSlider("Speed", "", 1000, 15, function(s) -- 500 (MaxValue) | 0 (MinValue)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

Tab1Section:NewSlider("Jump Power", "", 500, 5, function(s) -- 500 (MaxValue) | 0 (MinValue)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

Tab1Section:NewSlider("SliderText", "", 180, 70, function(s) -- 500 (MaxValue) | 0 (MinValue)
game.Workspace.CurrentCamera.FieldOfView = s
end)

Tab1Section:NewTextBox("Api Executer", "", function(txt)
game:GetService("StarterGui"):SetCore("SendNotification",{
	Title = "Executing Script", -- Required
	Text = "",
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150" -- Optional
})
game:GetService("StarterGui"):SetCore("SendNotification",{
	Title = "Script Executed", -- Required
	Text = "",
	Icon = "rbxthumb://type=Asset&id=9950668390&w=150&h=150" -- Optional
})
loadstring(txt)()
end)

Tab1Section:NewTextBox("Set Walkspeed","", function(txt) 
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)

Tab1Section:NewTextBox("Set Jumppower","Increases JP", function(txt)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end)

Tab1Section:NewTextBox("Set FOV [Normal Fov: 70]","", function(txt) 
game.Workspace.CurrentCamera.FieldOfView = txt
end)

Tab1Section:NewButton("Fly V3", "", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/RPv4GELs"))()
end)

Tab1Section:NewButton("Empty Serve/New Server", "", function()
local Http = game:GetService("HttpService")
local TPS = game:GetService("TeleportService")
local Api = "https://games.roblox.com/v1/games/"

local _place = game.PlaceId
local _servers = Api.._place.."/servers/Public?sortOrder=Asc&limit=100"
function ListServers(cursor)
   local Raw = game:HttpGet(_servers .. ((cursor and "&cursor="..cursor) or ""))
   return Http:JSONDecode(Raw)
end

local Server, Next; repeat
   local Servers = ListServers(Next)
   Server = Servers.data[1]
   Next = Servers.nextPageCursor
until Server

TPS:TeleportToPlaceInstance(_place,Server.id,game.Players.LocalPlayer)
end)

Tab1Section:NewButton("Big Head (Rthro Head)", "", function()
--body sizes: BodyHeightScale: 105%
--            BodyWidthScale: 100%
--            HeadScale: 100%
--            BodyProportionScale: 0%
--            AvatarPartScaleType: 100%


local LocalPlayer = game:GetService("Players").LocalPlayer
local Character = LocalPlayer.Character
local Humanoid = Character:FindFirstChildOfClass("Humanoid")

function rm()
	for i,v in pairs(Character:GetDescendants()) do
		if v:IsA("BasePart") then
			if v.Name == "Handle" or v.Name == "Head" then
				if Character.Head:FindFirstChild("OriginalSize") then
					Character.Head.OriginalSize:Destroy()
				end
			else
				for i,cav in pairs(v:GetDescendants()) do
					if cav:IsA("Attachment") then
						if cav:FindFirstChild("OriginalPosition") then
							cav.OriginalPosition:Destroy()  
						end
					end
				end
				v:FindFirstChild("OriginalSize"):Destroy()
				if v:FindFirstChild("AvatarPartScaleType") then
					v:FindFirstChild("AvatarPartScaleType"):Destroy()
				end
			end
		end
	end
end

rm()
wait(0.5)
Humanoid:FindFirstChild("BodyProportionScale"):Destroy()
wait(1)

rm()
wait(0.5)
Humanoid:FindFirstChild("BodyHeightScale"):Destroy()
wait(1)

rm()
wait(0.5)
Humanoid:FindFirstChild("BodyWidthScale"):Destroy()
wait(1)

rm()
wait(0.5)
Humanoid:FindFirstChild("BodyDepthScale"):Destroy()
wait(1)

rm()
wait(0.5)
Humanoid:FindFirstChild("HeadScale"):Destroy()
wait(1)
end)

Tab1Section:NewButton("Old Roblox Ui", "", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/kosuke14/REBOYHub/main/games/2016_Roblox.lua'))()
end)

Tab1Section:NewButton("Fps Boost", "", function()
local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
local g = game
local w = g.Workspace
local l = g.Lighting
local t = w.Terrain
t.WaterWaveSize = 0
t.WaterWaveSpeed = 0
t.WaterReflectance = 0
t.WaterTransparency = 0
l.GlobalShadows = false
l.FogEnd = 9e9
l.Brightness = 0
settings().Rendering.QualityLevel = "Level01"
for i, v in pairs(g:GetDescendants()) do
    if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
    elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
        v.Transparency = 1
    elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
        v.Lifetime = NumberRange.new(0)
    elseif v:IsA("Explosion") then
        v.BlastPressure = 1
        v.BlastRadius = 1
    elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") then
        v.Enabled = false
    elseif v:IsA("MeshPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
        v.TextureID = 10385902758728957
    end
end
for i, e in pairs(l:GetChildren()) do
    if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
        e.Enabled = false
    end
end
end)

Tab1Section:NewButton("Controll Npc {Need Keyboard}", "", function()
--[[ 
Hold LeftControl and Click an npc to control

Press Quote to return to your player

Hold LeftShift and press a Numpad key to save your current npc

Hold LeftControl and press a Numpad key to control the saved npc
]]

spawn(function()
  while wait() do
    game.Players.LocalPlayer.MaximumSimulationRadius = math.huge;
    setsimulationradius(math.huge);
  end
end)

local OGPN = game.Players.LocalPlayer.Name
local Player = game.Players.LocalPlayer
local Mouse = Player:GetMouse()

function Ctrl(NPC)
  Char = NPC
  Player.Character = Char
  workspace.CurrentCamera.CameraSubject = Char
  Char.Animate.Disabled = true
 wait(0.1)
  Char.Animate.Disabled = false
end

Mouse.Button1Down:connect(function()
  if game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and Mouse.Target ~= nil and Mouse.Target.Parent.Name ~= "Workspace" and Mouse.Target.Parent:FindFirstChildOfClass("Humanoid") ~= nil then
    Char = Mouse.Target.Parent
    Player.Character = Mouse.Target.Parent
    workspace.CurrentCamera.CameraSubject = Char
    Char.Animate.Disabled = true
   wait(0.1)
    Char.Animate.Disabled = false
  end
end)

Mouse.KeyDown:connect(function()
  if game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadOne) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    a = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadTwo) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    b = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadThree) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    c = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadFour) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    d = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadFive) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    e = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadSix) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    f = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadSeven) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    g = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadEight) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    h = Char
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadNine) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
    i = Char
  end
end)

Mouse.KeyDown:connect(function()
  if game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.Quote) then
    for i,v in pairs(game.Workspace:GetDescendants()) do
      if v.Name == OGPN and v.ClassName == 'Model' then
        Ctrl(v)
      end
    end
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadOne) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(a)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadTwo) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(b)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadThree) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(c)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadFour) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(d)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadFive) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(e)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadSix) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(f)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadSeven) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(g)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadEight) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(h)
  elseif game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.KeypadNine) and game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) and not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftShift) then
    Ctrl(i)
  end
end)
end)

Tab1Section:NewButton("Crash Server {R15 Layered Clothing}", "", function()
-- be R15 and wear layered clothing 
for _,s in pairs(game.Players.LocalPlayer.Character:GetDescendants()) 
do if s:IsA("Motor6D") 
and s.Name ~= "Neck" then local fard = s.Parent s:Destroy() 
fard.CFrame = CFrame.new(9e9 * _,9e9* _,9e9*_) 
wait() 
end 
end
end)

Tab1Section:NewButton("Anti Fling", "", function()
-- // Constants \\ --
-- [ Services ] --
local Services = setmetatable({}, {__index = function(Self, Index)
local NewService = game.GetService(game, Index)
if NewService then
Self[Index] = NewService
end
return NewService
end})

-- [ LocalPlayer ] --
local LocalPlayer = Services.Players.LocalPlayer

-- // Functions \\ --
local function PlayerAdded(Player)
   local Detected = false
   local Character;
   local PrimaryPart;

   local function CharacterAdded(NewCharacter)
       Character = NewCharacter
       repeat
           wait()
           PrimaryPart = NewCharacter:FindFirstChild("HumanoidRootPart")
       until PrimaryPart
       Detected = false
   end

   CharacterAdded(Player.Character or Player.CharacterAdded:Wait())
   Player.CharacterAdded:Connect(CharacterAdded)
   Services.RunService.Heartbeat:Connect(function()
       if (Character and Character:IsDescendantOf(workspace)) and (PrimaryPart and PrimaryPart:IsDescendantOf(Character)) then
           if PrimaryPart.AssemblyAngularVelocity.Magnitude > 50 or PrimaryPart.AssemblyLinearVelocity.Magnitude > 100 then
               if Detected == false then
                   game.StarterGui:SetCore("ChatMakeSystemMessage", {
                       Text = "Fling Exploit detected, Player: " .. tostring(Player);
                       Color = Color3.fromRGB(255, 200, 0);
                   })
               end
               Detected = true
               for i,v in ipairs(Character:GetDescendants()) do
                   if v:IsA("BasePart") then
                       v.CanCollide = false
                       v.AssemblyAngularVelocity = Vector3.new(0, 0, 0)
                       v.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
                       v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0)
                   end
               end
               PrimaryPart.CanCollide = false
               PrimaryPart.AssemblyAngularVelocity = Vector3.new(0, 0, 0)
               PrimaryPart.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
               PrimaryPart.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0)
           end
       end
   end)
end

-- // Event Listeners \\ --
for i,v in ipairs(Services.Players:GetPlayers()) do
   if v ~= LocalPlayer then
       PlayerAdded(v)
   end
end
Services.Players.PlayerAdded:Connect(PlayerAdded)

local LastPosition = nil
Services.RunService.Heartbeat:Connect(function()
   pcall(function()
       local PrimaryPart = LocalPlayer.Character.PrimaryPart
       if PrimaryPart.AssemblyLinearVelocity.Magnitude > 250 or PrimaryPart.AssemblyAngularVelocity.Magnitude > 250 then
           PrimaryPart.AssemblyAngularVelocity = Vector3.new(0, 0, 0)
           PrimaryPart.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
           PrimaryPart.CFrame = LastPosition

           game.StarterGui:SetCore("ChatMakeSystemMessage", {
               Text = "You were flung. Neutralizing velocity.";
               Color = Color3.fromRGB(255, 0, 0);
           })
       elseif PrimaryPart.AssemblyLinearVelocity.Magnitude < 50 or PrimaryPart.AssemblyAngularVelocity.Magnitude > 50 then
           LastPosition = PrimaryPart.CFrame
       end
   end)
end)
end)

Tab1Section:NewButton("Mario [R15]", "", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/mario-r15/main/Protected.lua'))()
end)

Tab1Section:NewButton("Rejoin Script", "", function()
game:GetService'TeleportService':TeleportToPlaceInstance(game.PlaceId,game.JobId,game:GetService'Players'.LocalPlayer)
end)

Tab1Section:NewButton("Leave And Join Ditector", "", function()
local function SendNotification(title,text,duration,...)
  game.StarterGui:SetCore("SendNotification", {
    Title = title;
    Text = text;
    Icon = "";
    Duration = duration;
  })
end

--Join Detecter

game.Players.ChildAdded:Connect(function(player)
  if not pcall (function()
  SendNotification("Player JOINED",""..player.Name.." has JOINED the game",5 )
  end) then
    print ("Error")
  end
  end)

--Leave Detecter
 
  game.Players.ChildRemoved:Connect(function(player)
  if not pcall (function()
  SendNotification("Player LEFT",""..player.Name.." has LEFT the game",4.4 )
  end) then
    print ("Error")
  end
  end)
  
  SendNotification("Loaded","Join and leave detector is loaded",2)
end)

Tab1Section:NewButton("Speed Tool", "", function()
--Made By Raspyredstoner
mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Speed Tool"
tool.Activated:connect(function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)
tool.Parent = game.Players.LocalPlayer.Backpack
end)

Tab1Section:NewButton("ShiftLock", "", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/WQ9NPeDS'))();
end)

Tab1Section:NewButton("Wall Walking", "", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
end)

Tab1Section:NewButton("Full Brightness", "", function()
    game:GetService("Lighting").Brightness = 2
game:GetService("Lighting").ClockTime = 14
game:GetService("Lighting").FogEnd = 100000
game:GetService("Lighting").GlobalShadows = false
game:GetService("Lighting").OutdoorAmbient = Color3.fromRGB(128, 128, 128)
end)

Tab1Section:NewButton("Steal Player Inventory", "FE in some games", function()
game.StarterGui:SetCore("SendNotification",  {
 Title = "Nofication";
 Text = "This script is FE is some games mainly in SCP games";
 Icon = "";
 Duration = 10;
})
for i,v in pairs (game.Players:GetChildren()) do
wait()
for i,b in pairs (v.Backpack:GetChildren()) do
b.Parent = game.Players.LocalPlayer.Backpack
end
end
end)

Tab1Section:NewButton("Chat Translator", "", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Language-translator-/main/Language%20translator", true))()
end)

Tab1Section:NewButton("Teleport Tool", "", function()
    mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Click Teleport"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
end)

Tab1Section:NewButton("Telekenisis Tool", "", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/alt1lr/lol-bu/main/README.md'))()
end)

local Tab1Section = Tab1:NewSection("Cape Script")

Tab1Section:NewButton("Fire Hub Cape", "", function()
local player = game:GetService("Players")

local lplr = player.LocalPlayer

if lplr.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then

      if lplr.Character:FindFirstChild("Torso") then

        torso = lplr.Character.Torso

      else

        torso = lplr.Character.UpperTorso

      end

      local CapeP = Instance.new("Part", torso.Parent)

      CapeP.Name = "Cape"

      CapeP.Anchored = false

      CapeP.CanCollide = false

      CapeP.TopSurface = 0

      CapeP.BottomSurface = 0

      CapeP.Color = Color3.fromRGB(0,0,0)

      CapeP.FormFactor = "Custom"

      CapeP.Size = Vector3.new(0.2,0.2,0.2)

      local decal = Instance.new("Decal", CapeP)

      decal.Texture = "rbxthumb://type=Asset&id=9950668390&w=150&h=150"

      decal.Face = "Back"

      local msh = Instance.new("BlockMesh", CapeP)

      msh.Scale = Vector3.new(9,17.5,0.5)

      local motor = Instance.new("Motor", CapeP)

      motor.Part0 = CapeP

      motor.Part1 = torso

      motor.MaxVelocity = 0.01

      motor.C0 = CFrame.new(0,1.75,0) * CFrame.Angles(0,math.rad(90),0)

      motor.C1 = CFrame.new(0,1,0.45) * CFrame.Angles(0,math.rad(90),0)

      local wave = false

      repeat wait(1/44)

        decal.Transparency = torso.Transparency

        local ang = 0.1

        local oldmag = torso.Velocity.magnitude

        local mv = 0.002

        if wave then

          ang = ang + ((torso.Velocity.magnitude/10) * 0.05) + 0.05

          wave = false

        else

          wave = true

        end

        ang = ang + math.min(torso.Velocity.magnitude/11, 0.5)

        motor.MaxVelocity = math.min((torso.Velocity.magnitude/111), 0.04) + mv

        motor.DesiredAngle = -ang

        if motor.CurrentAngle < -0.2 and motor.DesiredAngle > -0.2 then

          motor.MaxVelocity = 0.04

        end

        repeat wait() until motor.CurrentAngle == motor.DesiredAngle or math.abs(torso.Velocity.magnitude - oldmag) >= (torso.Velocity.magnitude/10) + 1

        if torso.Velocity.magnitude < 0.1 then

          wait(0.1)

        end

      until not CapeP or CapeP.Parent ~= torso.Parent

    end
end)

Tab1Section:NewButton("BH Cape", "British Hub Cape", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/CAPE"))()
end)

Tab1Section:NewButton("JN HH Gaminng Cape", "JN HH Gaming Cape", function()
local player = game:GetService("Players")

local lplr = player.LocalPlayer

if lplr.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then

      if lplr.Character:FindFirstChild("Torso") then

        torso = lplr.Character.Torso

      else

        torso = lplr.Character.UpperTorso

      end

      local CapeP = Instance.new("Part", torso.Parent)

      CapeP.Name = "Cape"

      CapeP.Anchored = false

      CapeP.CanCollide = false

      CapeP.TopSurface = 0

      CapeP.BottomSurface = 0

      CapeP.Color = Color3.fromRGB(34,34,34)

      CapeP.FormFactor = "Custom"

      CapeP.Size = Vector3.new(0.2,0.2,0.2)

      local decal = Instance.new("Decal", CapeP)

      decal.Texture = "rbxthumb://type=Asset&id=9685546949&w=150&h=150"

      decal.Face = "Back"

      local msh = Instance.new("BlockMesh", CapeP)

      msh.Scale = Vector3.new(9,17.5,0.5)

      local motor = Instance.new("Motor", CapeP)

      motor.Part0 = CapeP

      motor.Part1 = torso

      motor.MaxVelocity = 0.01

      motor.C0 = CFrame.new(0,1.75,0) * CFrame.Angles(0,math.rad(90),0)

      motor.C1 = CFrame.new(0,1,0.45) * CFrame.Angles(0,math.rad(90),0)

      local wave = false

      repeat wait(1/44)

        decal.Transparency = torso.Transparency

        local ang = 0.1

        local oldmag = torso.Velocity.magnitude

        local mv = 0.002

        if wave then

          ang = ang + ((torso.Velocity.magnitude/10) * 0.05) + 0.05

          wave = false

        else

          wave = true

        end

        ang = ang + math.min(torso.Velocity.magnitude/11, 0.5)

        motor.MaxVelocity = math.min((torso.Velocity.magnitude/111), 0.04) + mv

        motor.DesiredAngle = -ang

        if motor.CurrentAngle < -0.2 and motor.DesiredAngle > -0.2 then

          motor.MaxVelocity = 0.04

        end

        repeat wait() until motor.CurrentAngle == motor.DesiredAngle or math.abs(torso.Velocity.magnitude - oldmag) >= (torso.Velocity.magnitude/10) + 1

        if torso.Velocity.magnitude < 0.1 then

          wait(0.1)

        end

      until not CapeP or CapeP.Parent ~= torso.Parent

    end
end)

local Tab1Section = Tab1:NewSection("Gui Script")

Tab1Section:NewButton("Bang r15", "Find it out by yourself", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/bang/main/Protected%20(27).lua'))()
end)

Tab1Section:NewButton("Annoy Player", "", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/1cHdCvTF"))()
end)

Tab1Section:NewButton("Keyboard", "", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
local KeyboardguiWarriorRoberrVersion = Instance.new("ScreenGui")
local Drag = Instance.new("Frame")
local Close = Instance.new("TextButton")


KeyboardguiWarriorRoberrVersion.Name = "Keyboard gui WarriorRoberr Version"
KeyboardguiWarriorRoberrVersion.Parent = game.CoreGui
KeyboardguiWarriorRoberrVersion.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Drag.Name = "Drag"
Drag.Parent = KeyboardguiWarriorRoberrVersion
Drag.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Drag.BorderSizePixel = 0
Drag.Position = UDim2.new(0.147916675, 0, 0.0593749993, 0)
Drag.Size = UDim2.new(0, 270, 0, 30)
Drag.Active = true
Drag.Draggable = true

Close.Name = "Close"
Close.Parent = Drag
Close.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.999839723, 0, -0.00729167089, 0)
Close.Size = UDim2.new(0, 30, 0, 30)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextSize = 35.000
Close.MouseButton1Click:Connect(function()
	KeyboardguiWarriorRoberrVersion:Destroy()
end)
game.CoreGui["BUNB0yBUN BOARD"].KeyBoard.Parent = Drag
game.CoreGui["BUNB0yBUN BOARD"]:Destroy()
game.CoreGui["Keyboard gui WarriorRoberr Version"].Drag.KeyBoard.Bunb0ybun.Text = "MADE BY WARRIORROBERR BETTER VERSION "
game.CoreGui["Keyboard gui WarriorRoberr Version"].Drag.KeyBoard.Position = UDim2.new(0, 0, 0, 35)
game.CoreGui["Keyboard gui WarriorRoberr Version"].Drag.KeyBoard.Bunb0ybun.TextSize = 10
end)

Tab1Section:NewButton("Sussy Hub", "", function()
-- FE SussyHub Made by Nil <3
-- Mizt Source by Melon <3
loadstring(game:HttpGet(('https://gist.githubusercontent.com/Nilrogram/8b0c8bd710be142f383c71f79279752c/raw/e4fb01a7de7cd498bb53270d2ad191dfab268a88/FE%2520SussyHub'),true))();
end)

Tab1Section:NewButton("Yeet Troll Face Edition", "", function()
-- I DONT OWN THIS SCRIPT

local lp = game:FindService("Players").LocalPlayer

local function gplr(String)
	local Found = {}
	local strl = String:lower()
	if strl == "all" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			table.insert(Found,v)
		end
	elseif strl == "others" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name ~= lp.Name then
				table.insert(Found,v)
			end
		end 
	elseif strl == "me" then
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name == lp.Name then
				table.insert(Found,v)
			end
		end 
	else
		for i,v in pairs(game:FindService("Players"):GetPlayers()) do
			if v.Name:lower():sub(1, #String) == String:lower() then
				table.insert(Found,v)
			end
		end 
	end
	return Found 
end

local function notif(str,dur)
	game:FindService("StarterGui"):SetCore("SendNotification", {
		Title = "yeet gui",
		Text = str,
		Icon = "rbxassetid://2005276185",
		Duration = dur or 3
	})
end

--// sds

local h = Instance.new("ScreenGui")
local Main = Instance.new("ImageLabel")
local Top = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")

h.Name = "h"
h.Parent = game:GetService("CoreGui")
h.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = h
Main.Active = true
Main.Draggable = true
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.174545452, 0, 0.459574461, 0)
Main.Size = UDim2.new(0, 454, 0, 218)
Main.Image = "rbxassetid://2005276185"

Top.Name = "Top"
Top.Parent = Main
Top.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Top.BorderSizePixel = 0
Top.Size = UDim2.new(0, 454, 0, 44)

Title.Name = "Title"
Title.Parent = Top
Title.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0, 0, 0.295454562, 0)
Title.Size = UDim2.new(0, 454, 0, 30)
Title.Font = Enum.Font.SourceSans
Title.Text = "FE Yeet Gui (trollface edition)"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

TextBox.Parent = Main
TextBox.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0704845786, 0, 0.270642221, 0)
TextBox.Size = UDim2.new(0, 388, 0, 62)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderText = "Who do i destroy(can be shortened)"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

TextButton.Parent = Main
TextButton.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.10352423, 0, 0.596330225, 0)
TextButton.Size = UDim2.new(0, 359, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Cheese em'"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

TextButton.MouseButton1Click:Connect(function()
	local Target = gplr(TextBox.Text)
	if Target[1] then
		Target = Target[1]
		
		local Thrust = Instance.new('BodyThrust', lp.Character.HumanoidRootPart)
		Thrust.Force = Vector3.new(9999,9999,9999)
		Thrust.Name = "YeetForce"
		repeat
			lp.Character.HumanoidRootPart.CFrame = Target.Character.HumanoidRootPart.CFrame
			Thrust.Location = Target.Character.HumanoidRootPart.Position
			game:FindService("RunService").Heartbeat:wait()
		until not Target.Character:FindFirstChild("Head")
	else
		notif("Invalid player")
	end
end)
end)

Tab2Section:NewButton("Teleport to Game", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-125, 48, 10)
end)

Tab2Section:NewButton("Teleport to Lobby", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-245, 180, 325)
end)

Tab2Section:NewButton("No Fall Damage", "", function()
game.Players.LocalPlayer.Character.FallDamageScript:Destroy()
end)

Tab2Section:NewButton("Enable Ballon Mode", "", function()
    workspace.Gravity = 60
end)

Tab2Section:NewButton("Disable Ballon Mode", "", function()
    workspace.Gravity = 200
    end)

Tab2Section:NewButton("Auto Farm", "", function()
while true do wait()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-248, 180, 290)
end
end)

Tab2Section:NewButton("UnAuto Farm", "", function()
    game.Players.LocalPlayer.Character:Destroy()
game.Players.LocalPlayer.Character.Script:Destroy()
end)

Tab3Section:NewButton("Teleport to Library", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(180, -11, 1159)
wait(1)
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(240, -11, 1156)
end)

Tab3Section:NewButton("Library Password Books", "", function()
local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Books Password",
    Text = "Yello,Red,Pink,Cyan,LightGreen",
    Duration = 10,
})

end)

Tab3Section:NewButton("Teleport to End", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-55, -360, 9478)
end)

Tab3Section:NewButton("Auto Farm", "", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/nucy5Uw8'))();
end)
    

local Tab3Section = Tab3:NewSection("Teleport to Teams")

Tab3Section:NewButton("White Team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-42, -9, -614)
end)

Tab3Section:NewButton("Black Team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-576, -9, -122)
end)

Tab3Section:NewButton("Red Team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(479, -9, -54)
end)

Tab3Section:NewButton("Green team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-596, -9, 302)
end)

Tab3Section:NewButton("Blue Team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(474, -9, 293)
end)

Tab3Section:NewButton("Magenta Team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(469, -9, 617)
end)

Tab3Section:NewButton("Yellow Team", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-586, -9, 652)
end)

local Tab4 = Window:NewTab("Lumber Tycoon 2")
local Tab4Section = Tab4:NewSection("Lumber Tycoon 2")

Tab4Section:NewButton("Dupe Axe", "", function()
local plr = game:service'Players'.LocalPlayer

function SafeRespawn()
    plr.Character.Head:Destroy()
end

function Dupe()
    SafeRespawn()
    for i,v in pairs(plr.Backpack:GetChildren()) do
        if v.Name == "Tool" then
            game:GetService("ReplicatedStorage").Interaction.ClientInteracted:FireServer(v,"Drop tool",plr.Character.Torso.CFrame * CFrame.new(0,5,0))
        end
    end
end
Dupe()
end)

Tab4Section:NewButton("Dupe Money", "", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/Duy5Lqyk'))();
end)

Tab4Section:NewButton("Free Land", "", function()
    for a,b in pairs(workspace.Properties:GetChildren()) do 
    if b:FindFirstChild("Owner") and b:FindFirstChild("OriginSquare") and b.Owner.Value == nil then 
        game.ReplicatedStorage.PropertyPurchasing.ClientPurchasedProperty:FireServer(b, b.OriginSquare.OriginCFrame.Value.p + Vector3.new(0,3,0))
 wait(0.5)
        Instance.new('RemoteEvent', game:service'ReplicatedStorage'.Interaction).Name = "Ban"
	for i,v in pairs(game.Workspace.Properties:GetChildren()) do
		if v.Owner.Value == game.Players.LocalPlayer then
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame + Vector3.new(0,10,0)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
		end
	end
    end
end
end)

Tab4Section:NewButton("Max Land", "", function()
    for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
        if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
            base = v
            square = v.OriginSquare
            end
        end
    function makebase(pos)
        local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
        Event:FireServer(base, pos)
        end
    local spos = square.Position
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 80))

    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 80))
end)

local Tab4Section = Tab4:NewSection("Teleport to Places")

Tab4Section:NewButton("Spawn", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(153, 3, 61)
end)

Tab4Section:NewButton("Volcano", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1567, 623, 1085)
end)

Tab4Section:NewButton("Cave", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(3573, -181, 431)
end)

Tab4Section:NewButton("Links Logic", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(4607, 7, -798)
end)

Tab4Section:NewButton("Fancy Furnishings", "", function()
    game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(491, 3, -1720)
end)

Tab4Section:NewButton("Swamp", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1209, 132, -801)
end)

Tab4Section:NewButton("Palm Island", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(2549, -6, -42)
end)

Tab4Section:NewButton("Bobs Shack", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(237, 8, -2538)
end)

Tab4Section:NewButton("Shrine Of Sight", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1605, 195, 926)
end)

Tab4Section:NewButton("Boxed Cars", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(509, 3, -1463)
end)

Tab4Section:NewButton("Dock", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(1134, -1, -206)
end)

Tab4Section:NewButton("Bridge", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(113, 11, -977)
end)

Tab4Section:NewButton("Fine Arts Shop", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(5212, -166, 720)
end)

Tab4Section:NewButton("Strange Man", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(1068, 17, 1138)
end)

Tab4Section:NewButton("End Times", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(113, -213, -951)
end)

Tab4Section:NewButton("Snow Island", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(1445, 412, 3202)
end)


Tab5Section:NewButton("Anti Cheat Bypass", "", function()
local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Anti Cheat Bypass",
    Text = "Loading....",
    Duration = 10,
})
wait(3.5)
local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "Anti Cheat Bypass",
    Text = "Successful!",
    Duration = 10,
})
wait()
for a,b in pairs(getgc()) do if typeof(b) == 'function' then if debug.getinfo(b).name == 'kick' then
hookfunction(debug.getinfo(b).func,

function()
print'game tried to kick'
end) end end end
print'anticheat bypassed'
end)

Tab5Section:NewButton("Teleport To Top", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-110, 254, 49)
end)

Tab5Section:NewButton("Teleport to Start", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-21, -11, 48)
end)

Tab5Section:NewButton("Auto Win", "", function()
while true do wait()
    game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-118, 255, 49)
end
end)

Tab5Section:NewButton("Disable Auto Win", "", function()
    game.Players.LocalPlayer.Character:Destroy()
game.Players.LocalPlayer.Character.Script:Destroy()
end)

local Tab6 = Window:NewTab("Area51")
local Tab6Section = Tab6:NewSection(" Area 51")

local Tab7 = Window:NewTab("Big Brain Simulator")
local Tab7Section = Tab7:NewSection(" Big Brain Simulator")

local Tab8 = Window:NewTab("SuperNaturalSimulator")
local Tab8Section = Tab8:NewSection(" Super Natural Simulator ")

local Tab9 = Window:NewTab("Ninja Legends")
local Tab9Section = Tab9:NewSection(" Ninja Legends ")

local Tab10 = Window:NewTab("Other Gui")
local Tab10Section = Tab10:NewSection("Credits:")
local Tab10Section = Tab10:NewSection("Lots Of Script Is From V3rmillion")
local Tab10Section = Tab10:NewSection("Made By alt1lr#9459")
local Tab10Section = Tab10:NewSection("Ui Made By Kavo Ui Libary")
local Tab10Section = Tab10:NewSection("Kavo Ui Made By Xheptc")
local Tab10Section = Tab10:NewSection("Other Gui:")

Tab6Section:NewButton("Pack A Punch", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(278, 323, 785)
end)

Tab6Section:NewButton("Execution Room [Enside]", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(30.9760799407959, 313.500244140625, 204.16676330566406)
end)

Tab6Section:NewButton("Execution Room [Outside]", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(38.9072265625, 313.4998779296875, 203.27430725097656)
end)

Tab6Section:NewButton("Sewer", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(63.21028137207031, 271.7001953125, 206.32199096679688)
end)

Tab6Section:NewButton("Under Ground", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(279.2727355957031, 259.6999206542969, 356.2850646972656)
end)

Tab6Section:NewButton("Ammo", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(186.50311279296875, 313.5, 395.2683410644531)
end)

Tab6Section:NewButton("Lab", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-48.30491256713867, 303.49969482421875, 573.6751098632812)
end)

Tab6Section:NewButton("Armory", "", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-169.04812622070312, 293.5002136230469, 316.7572937011719)
end)

Tab6Section:NewButton("Gets All Guns", "", function()
run = not run
--Bring Part
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Hitbox" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait(1)
--tp part ps
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Hitbox" then
         	child.CFrame = CFrame.new(472, 551, 427)
		end
  	end
end)

Tab6Section:NewButton("Become Monster", "", function ()
run = not run
--Bring Part
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "TheButton" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait(1)
--tp part ps
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "TheButton" then
         	child.CFrame = CFrame.new(401, 509.7, 392)
		end
  	end
end)

Tab6Section:NewButton("Get Ammo", "", function()
run = not run
--Bring Part
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Box" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait(0.5)
--tp part ps
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Box" then
         	child.CFrame = CFrame.new(184, 311, 437)
		end
  	end
end)

Tab6Section:NewButton("Get All Papers", "", function()
run = not run
--Bring Part
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Paper" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait(1)
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Paper" then
         	child.CFrame = CFrame.new(408, 551, 404)
		end
  	end
end)

Tab6Section:NewButton("Remove Fog", "", function ()
    for i,v in pairs(game.Lighting:GetChildren()) do
			if v:IsA("Script") == false and v:IsA("LocalScript") == false then
				v:remove()
		end
	end
while true and wait() do
game.Lighting.FogEnd = math.huge
		game.Lighting.FogStart = 0
		
		game.Lighting.ClockTime=12
	game.Lighting.Brightness = 2
		game.Lighting.Ambient = Color3.fromRGB(167, 167, 167)
		game.Lighting.OutdoorAmbient = Color3.fromRGB(167, 167, 167)
end
end)

Tab7Section:NewButton("Auto Read", "", function()
local range = 1000

local player = game:GetService("Players").LocalPlayer

game:GetService("RunService").RenderStepped:Connect(function()
    local p = game.Players:GetPlayers()
    for i = 2, #p do local v = p[i].Character
        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and player:DistanceFromCharacter(v.HumanoidRootPart.Position) <= range then
            local tool = player.Character and player.Character:FindFirstChildOfClass("Tool")
            if tool and tool:FindFirstChild("Handle") then
                tool:Activate()
                for i,v in next, v:GetChildren() do
                    if v:IsA("BasePart") then
                        firetouchinterest(tool.Handle,v,0)
                        firetouchinterest(tool.Handle,v,1)
                    end
                end
            end
        end
    end
end)
end)
    
Tab7Section:NewButton("Teleport to Sell", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-55, 3, -46)
end)

Tab7Section:NewButton("Unlock all Gamepasses", "", function()
game:GetService("Players").LocalPlayer.Gamepasses["2xCoins"].Value = true
game:GetService("Players").LocalPlayer.Gamepasses.Running.Value = true
game:GetService("Players").LocalPlayer.Gamepasses.FastReading.Value = true
game:GetService("Players").LocalPlayer.Gamepasses.Balloon.Value = true
game:GetService("Players").LocalPlayer.Gamepasses.DoubleJump.Value = true
game:GetService("Players").LocalPlayer.Gamepasses.InfiniteBrainCapacity.Value = true
end)

Tab7Section:NewButton("Unlock All Portals", "", function()
game:GetService("Players")["LocalPlayer"].Portals.PeacefulFields.Value = true
game:GetService("Players")["LocalPlayer"].Portals.SnowySnow.Value = true
game:GetService("Players")["LocalPlayer"].Portals.Dunes.Value = true
game:GetService("Players")["LocalPlayer"].Portals.FloatingRock.Value = true
game:GetService("Players")["LocalPlayer"].Portals.SpaceBubble.Value = true
game:GetService("Players")["LocalPlayer"].Portals.Mars.Value = true
game:GetService("Players")["LocalPlayer"].Portals.Moon.Value = true
end)

local Tab7Section = Tab7:NewSection("Teleport Places")

Tab7Section:NewButton("Mars", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-17, 76667, 162)
end)

Tab7Section:NewButton("Moon", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-15, 52667, 186)
end)

Tab7Section:NewButton("Space Bubble", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-16, 34716, 93)
end)

Tab7Section:NewButton("Floating Rock", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-16, 17881, 94)
end)

Tab7Section:NewButton("Dunes", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-16, 8313, 93)
end)

Tab7Section:NewButton("Snowy Snow", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-29, 3503, 96)
end)

Tab7Section:NewButton("Peaceful Fields", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-28, 1022, 94)
end)

Tab8Section:NewToggle("Auto Sell", "", function(state)
    if state then
_G.sell = true
while _G.sell do
    wait(10) -- its good delay didnt change
local args = {
    [1] = {
        [1] = "SellMuscle"
    }
}

game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
end
    else
_G.sell = false
    end
end)

Tab8Section:NewToggle("Auto Gain", "", function(state)
    if state then
_G.gain = true
while _G.gain do
    wait(0.0000000000000000000001) -- its good delay didnt change
local args = {
    [1] = {
        [1] = "GainMuscle"
    }
}

game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
end
    else
_G.gain = false
    end
end)
Tab8Section:NewTextBox("Auto Sell", "ARE YOU DUMD?! FUCK UR SELF", function(txt)
_G.sell = true
while _G.sell do
    wait(txt) -- its good delay didnt change
local args = {
    [1] = {
        [1] = "SellMuscle"
    }
}

game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
end
end)

Tab8Section:NewTextBox("Auto Gain", "ARE YOU DUMD?! FUCK UR SELF", function(txt)
_G.gain = true
while _G.gain do
    wait(txt) -- its good delay didnt change
local args = {
    [1] = {
        [1] = "GainMuscle"
    }
}

game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
end
end)

Tab9Section:NewToggle("Auto Swing", "Auto Swing", function(v)
getgenv().autoswing = v
        while true do
            if not getgenv().autoswing then return end
            for _,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                if v:FindFirstChild("ninjitsuGain") then
                    game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
                    break
                end
            end
            local A_1 = "swingKatana"
            local Event = game:GetService("Players").LocalPlayer.ninjaEvent
            Event:FireServer(A_1)
            wait(0.1)
    end
end)

Tab9Section:NewToggle("Auto Sell", "Auto Sell", function(state)
getgenv().autosell = v
        while true do
            if getgenv().autoswing == false then return end
            game:GetService("Workspace").sellAreaCircles["sellAreaCircle16"].circleInner.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            wait(0.1)
            game:GetService("Workspace").sellAreaCircles["sellAreaCircle16"].circleInner.CFrame = CFrame.new(0,0,0)
            wait(0.1)
    end
end)

local Tab9Section = Tab9:NewSection("Auto Buy")

Tab9Section:NewToggle("Auto Buy Belts", "Auto Buy", function(state)
getgenv().buybelts = v
        while true do
            if not getgenv().buybelts then return end
            local A_1 = "buyAllBelts"
            local A_2 = "Inner Peace Island"
            local Event = game:GetService("Players").LocalPlayer.ninjaEvent
            Event:FireServer(A_1, A_2)
            wait(0.5)
    end
end)

Tab9Section:NewToggle("Auto Buy Katana", "Auto Buy", function(state)
getgenv().buyKatana = v
        while true do
            if not getgenv().buybelts then return end
            local A_1 = "buyAllKatana"
            local A_2 = "Inner Peace Island"
            local Event = game:GetService("Players").LocalPlayer.ninjaEvent
            Event:FireServer(A_1, A_2)
            wait(0.5)
    end
end)

local Tab9Section = Tab9:NewSection("Unluck All Island")

Tab9Section:NewButton("Unluck All Island", "Unluck All", function()
local oldcframe = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
        for _,v in pairs(game:GetService("Workspace").islandUnlockParts:GetChildren()) do
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
            wait(0.1)
        end
        wait(0.1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = oldcframe
end)

local Tab10Section = Tab10:NewSection("British Hub")

Tab10Section:NewButton("British Hub V4", "", function()
local StarterGui = game:GetService("StarterGui")
local bindable1 = Instance.new("BindableFunction")

function bindable1.OnInvoke(response)
setclipboard('https://discord.gg/bK3ruZfwaE')
end

StarterGui:SetCore("SendNotification", {
	Title = "Discord",
	Text = "Join Discord",
	Duration = 3,
	Callback = bindable1,
	Button1 = "Sure",
})
wait(2.1)
loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/Bri%20hub"))()
end)

local Tab10Section = Tab10:NewSection("Fire Hub [2]")

Tab10Section:NewButton("Fire Hub [2]", "", function()
local message = Instance.new("Message",workspace) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1) 

message.Text = "Loading..." 

wait(1) 

message.Text = "Loading" 

wait(1) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1) 

message.Text = "Loading..." 

wait(1) 

message.Text = "Loading" 

wait(1) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1.8) 

message:Destroy()
local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Fire Hub [2]", "BloodTheme")

local Tab1 = Window:NewTab("SwordMan Simulator")
local Tab1Section = Tab1:NewSection("SwordMan Simulator")

local Tab2 = Window:NewTab("Eating Simulator")
local Tab2Section = Tab2:NewSection("Eating Simulator")

local Tab3 = Window:NewTab("Anime Sword Simulator")
local Tab3Section = Tab3:NewSection("Anime Sword Simulator")

local Tab5 = Window:NewTab("Step Counter")
local Tab5Section = Tab5:NewSection(" Step Counter")

Tab1Section:NewToggle("Kill Farm", "", function(state)
    if state then
while true do wait(1)
    getgenv().autokill = true
 
if getgenv().autokill then
task.spawn(function()
while getgenv().autokill do
for I, V in pairs(game.Players:GetChildren()) do
local NewPlayerCFrame = V.Character.HumanoidRootPart.CFrame
 
if workspace[V.Name]:FindFirstChild("ForceField") then
print("User is in the safe zone/has a force field.")
else
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = NewPlayerCFrame  
wait(0.5)
getgenv().autokill = false
end
end
end
end)
end
end
    else
game:GetService'TeleportService':TeleportToPlaceInstance(game.PlaceId,game.JobId,game:GetService'Players'.LocalPlayer)
    end
end)

Tab1Section:NewButton("Claim All Chest", "", function()
local old = game.Players.LocalPlayer.Character:getChildren()
for i=1,#old do
if old[i].Name == "HumanoidRootPart" then
lastPos = old[i].CFrame
end
end
wait()
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(4, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(657, 556, -203)})
tween:Play()
wait(5)
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(4, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(706, 554, -753)})
tween:Play()
wait(5)
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(4, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(1305, 555, -68)})
tween:Play()
wait(5)
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(1, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(1323, 554, -51)})
tween:Play()
wait(1)
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(4, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(382, 555, 953)})
tween:Play()
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(4, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-212, 556, 242)})
tween:Play()
wait(5)
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(4, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(432, 555, 960)})
tween:Play()
wait(5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = lastPos
end)

Tab1Section:NewButton("Auto Click", "", function()
local range = 1000

local player = game:GetService("Players").LocalPlayer

game:GetService("RunService").RenderStepped:Connect(function()
    local p = game.Players:GetPlayers()
    for i = 2, #p do local v = p[i].Character
        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and player:DistanceFromCharacter(v.HumanoidRootPart.Position) <= range then
            local tool = player.Character and player.Character:FindFirstChildOfClass("Tool")
            if tool and tool:FindFirstChild("Handle") then
                tool:Activate()
                for i,v in next, v:GetChildren() do
                    if v:IsA("BasePart") then
                        firetouchinterest(tool.Handle,v,0)
                        firetouchinterest(tool.Handle,v,1)
                    end
                end
            end
        end
    end
end)
end)

local Tab1Section = Tab1:NewSection("Teleport")

Tab1Section:NewButton("Artic Island", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(869, 553, 47)
end)

Tab1Section:NewButton("King Territory", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(545, 570, 211)
end)

Tab1Section:NewButton("Marine Island", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(511, 553, -349)
end)

Tab2Section:NewToggle("Auto Sell", "", function(state)
    if state then
local range = 1000

local player = game:GetService("Players").LocalPlayer

game:GetService("RunService").RenderStepped:Connect(function()
    local p = game.Players:GetPlayers()
    for i = 2, #p do local v = p[i].Character
        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and player:DistanceFromCharacter(v.HumanoidRootPart.Position) <= range then
            local tool = player.Character and player.Character:FindFirstChildOfClass("Tool")
            if tool and tool:FindFirstChild("Handle") then
                tool:Activate()
                for i,v in next, v:GetChildren() do
                    if v:IsA("BasePart") then
                        firetouchinterest(tool.Handle,v,0)
                        firetouchinterest(tool.Handle,v,1)
                    end
                end
            end
        end
    end
end)
    else
--active loop
getgenv().autosell = true
 
if getgenv().autosell then
task.spawn(function()
while getgenv().autosell do
for I, V in pairs(game.Players:GetChildren()) do
--Save ps
local old = game.Players.LocalPlayer.Character:getChildren()
for i=1,#old do
if old[i].Name == "HumanoidRootPart" then
lastPos = old[i].CFrame
end
end
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-66, 10, 115)
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = lastPos
wait(10)
end
end
end)
end
    end
end)

Tab1Section:NewToggle("Auto Sell", "", function(state)
    if state then
--active loop
getgenv().autosell = true
 
if getgenv().autosell then
task.spawn(function()
while getgenv().autosell do
for I, V in pairs(game.Players:GetChildren()) do
--Save ps
local old = game.Players.LocalPlayer.Character:getChildren()
for i=1,#old do
if old[i].Name == "HumanoidRootPart" then
lastPos = old[i].CFrame
end
end
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-66, 10, 115)
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = lastPos
wait(10)
end
end
end)
end
    else
getgenv().autosell = false
    end
end)

local Tab2Section = Tab2:NewSection("Teleport")

Tab2Section:NewButton("Candy Island", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-348, 7042, 803)
end)

Tab2Section:NewButton("Soda Island Island", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-121, 2062, 350)
end)

Tab2Section:NewButton("Shop", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-142, 11, 120)
end)

Tab3Section:NewToggle("Auto Click", "", function(state)
    if state then
-----auto Tap
getgenv().autotap = true
while getgenv().autotap == true do
   task.wait()
local args = {
   [1] = {}
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("combat attack"):FireServer(unpack(args))
end
    else
getgenv().autotraining = false
    end
end)

Tab3Section:NewToggle("Auto Rebrith", "", function(state)
    if state then
getgenv().autorebirth = true -- change to false to stop
while getgenv().autorebirth == true do
   task.wait()
local args = {
   [1] = {
       [1] = 1
   }
}

game:GetService("ReplicatedStorage").Assets.Events.rebirth:FireServer(unpack(args))
end
    else
getgenv().autorebirth = false
    end
end)

Tab3Section:NewToggle("Auto Train", "", function(state)
    if state then
getgenv().autotraining = true
while getgenv().autotraining == true do
   task.wait()
local args = {
   [1] = {
       [1] = workspace.__MAP.Workouts.Training
   }
}

game:GetService("ReplicatedStorage").Assets.Events.training:InvokeServer(unpack(args))
end
    else

    end
end)

Tab3Section:NewButton("Redeem All Codes", "", function()
------Redeem All Codes
local args = {
   [1] = {
       [1] = "levelup"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "energym"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "awaitseason"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "gmarket"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "???"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "clashzone_fc"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "gseller"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
task.wait(1)
local args = {
   [1] = {
       [1] = "release"
   }
}

game:GetService("ReplicatedStorage").Assets.Events:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
end)

Tab5Section:NewToggle("Auto Rebirth", "", function(state)
    if state then
getgenv().autoRb = true
while getgenv().autoRb == true do
local args = {
[1] = "rebirthrequest"
}
game:GetService("ReplicatedStorage").rebirthrequest:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv()autoRb = false
    end
end)

Tab5Section:NewToggle("Auto Step", "", function(state)
    if state then
getgenv().autostep = true
while getgenv().autostep == true do
local args = {
[1] = "stepclickrequest"
}
game:GetService("ReplicatedStorage").stepclickrequest:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autostep = false
    end
end)

Tab5Section:NewToggle("Auto Sell", "", function(state)
    if state then
getgenv().autoSell = true
while getgenv().autoSell == true do
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "SellArea" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait()
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "SellArea" then
         	child.CFrame = CFrame.new(-65, 1, 66)
         	wait(10)
		end
  	end
end
    else
getgenv().autoSell = false
    end
end)

Tab5Section:NewToggle("Auto Get Piece", "", function(state)
    if state then
getgenv().autoPiece = true
while getgenv().autoPiece == true do
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "5piece" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "10piece" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "20piece" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "50piece" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait(5)
end
    else
getgenv().autoPiece = false
    end
end)

Tab5Section:NewToggle("Auto Upgrade Step", "", function(state)
    if state then
getgenv().autoUpg = true
while getgenv().autoUpg == true do
local args = {
[1] = "upgrademysteps"
}
game:GetService("ReplicatedStorage").upgrademysteps:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autoUpg = false
    end
end)

Tab5Section:NewToggle("Auto Upgrade Max", "", function(state)
    if state then
getgenv().autoUpgm = true
while getgenv().autoUpgm == true do
local args = {
[1] = "upgrademymaxsteps"
}
game:GetService("ReplicatedStorage").upgrademymaxsteps:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autoUpgm = false
    end
end)

local Tab4 = Window:NewTab("Nen Fighting Simulator")
local Tab4Section = Tab4:NewSection("Nen Fighting Simulator")

local Tab6 = Window:NewTab("Tower Of Hell")
local Tab6Section = Tab6:NewSection("Tower Of Hell")

local Tab7 = Window:NewTab("Prison Life")
local Tab7Section = Tab7:NewSection("Prison Life")

local Tab8 = Window:NewTab("Gym Training")
local Tab8Section = Tab8:NewSection("Gym Training")

local Tab9 = Window:NewTab("Eating Simulator")
local Tab9Section = Tab9:NewSection("Eating Simulator")

local Tab10 = Window:NewTab("Other Gui")
local Tab10Section = Tab10:NewSection("Credits In Fire Hub [3]")

Tab4Section:NewToggle("Auto Strenght", "", function(state)
    if state then
------Auto Strength
getgenv().autostr = true
while getgenv().autostr == true do
local args = {
[1] = "str"
}
game:GetService("ReplicatedStorage").Remotes.train:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autostr = false
    end
end)

Tab4Section:NewToggle("Auto Agility", "", function(state)
    if state then
------Auto Agility
getgenv().autoagi = true
while getgenv().autoagi == true do
local args = {
[1] = "agi"
}
game:GetService("ReplicatedStorage").Remotes.train:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autoagi = false
    end
end)

Tab4Section:NewToggle("Auto Nen", "", function(state)
    if state then
-----Auto Nen
getgenv().autonen = true
while getgenv().autonen == true do
local args = {
[1] = "nen"
}
game:GetService("ReplicatedStorage").Remotes.train:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autonen = false
    end
end)

Tab4Section:NewToggle("Auto Durability", "", function(state)
    if state then
------Auto Durability
getgenv().autodura = true
while getgenv().autodura == true do
local args = {
[1] = "dur"
}
game:GetService("ReplicatedStorage").Remotes.train:FireServer(unpack(args))
wait(0.1)
end
    else
getgenv().autodura = false
    end
end)

Tab6Section:NewToggle("Auto Farm 1", "", function(state)
    if state then
while true do wait(0.1)
local endzone = game.Workspace.tower.sections.finish.FinishGlow.CFrame
 
    local player = game.Players.LocalPlayer.Character
    player.HumanoidRootPart.CFrame = endzone
wait(1)
end
    else
game:GetService'TeleportService':TeleportToPlaceInstance(game.PlaceId,game.JobId,game:GetService'Players'.LocalPlayer)
    end
end)

Tab6Section:NewButton("Get Tool", "", function()
    for _,e in pairs(game.Players.LocalPlayer.Backpack:GetDescendants()) do
        if e:IsA("Tool") then
        e:Destroy()
        end
        end
        wait() 
        for _,v in pairs(game.ReplicatedStorage.Gear:GetDescendants()) do
        if v:IsA("Tool") then
        local CloneThings = v:Clone()
        wait()
        CloneThings.Parent = game.Players.LocalPlayer.Backpack
 
        end
        end
end)

Tab6Section:NewButton("God Mode", "", function()
for i,v in pairs(game:GetService("Workspace").tower:GetDescendants()) do
        if v:IsA("BoolValue") and v.Name == "kills" then
            v.Parent:Destroy()
        end
    end
end)

local Tab7Section = Tab7:NewSection("Guns")

Tab7Section:NewDropdown("Give Gun {M4A1 Need Gamepass}", "Gives  Gun", {"M9", "Remington 870", "AK-47", "M4A1"}, function(v)
   local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver[v].ITEMPICKUP
   local Event = game:GetService("Workspace").Remote.ItemHandler
   Event:InvokeServer(A_1)
end)

Tab7Section:NewDropdown("Gun Mod", "Makes the gun op", {"M9", "Remington 870", "AK-47"}, function(v)
      local module = nil
      if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(v) then
          module = require(game:GetService("Players").LocalPlayer.Backpack[v].GunStates)
      elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild(v) then
          module = require(game:GetService("Players").LocalPlayer.Character[v].GunStates)
      end
      if module ~= nil then
          module["MaxAmmo"] = math.huge
          module["CurrentAmmo"] = math.huge
          module["StoredAmmo"] = math.huge
          module["FireRate"] = 0.000001
          module["Spread"] = 0
          module["Range"] = math.huge
          module["Bullets"] = 10
          module["ReloadTime"] = 0.000001
          module["AutoFire"] = true
     end
end)

local Tab7Section = Tab7:NewSection("Teleports")

Tab7Section:NewButton("Outside Of Outside Prison", "Teleports You outside of the prison!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(451.6684265136719, 98.0399169921875, 2216.338134765625)
end)
            
Tab7Section:NewButton("Cafeteria", "Teleports you to the Cafeteria!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(918.994873046875, 99.98993682861328, 2325.73095703125)
end)

Tab7Section:NewButton("Prison Yard", "Teleports You to the Prison Yard", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(736.4671630859375, 97.99992370605469, 2517.583740234375)
end)
            
Tab7Section:NewButton("Kitchen", "Teleports You to the Kitchen!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(906.641845703125, 99.98993682861328, 2237.67333984375)
end)
            
Tab7Section:NewButton("Prison Cells", "Teleports You to the Prison Cells!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(919.5551147460938, 99.98998260498047, 2441.700927734375)
end)
            
Tab7Section:NewButton("Surveilance Room", "Teleports You to the Surveilance Room!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(795.251953125, 99.98998260498047, 2327.720703125)
end)
            
Tab7Section:NewButton("Break Room", "Teleports You to the Break Room!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(800.0896606445312, 99.98998260498047, 2266.71630859375)
end)
            
Tab7Section:NewButton("Police Armory", "Teleports You to the Police Armory!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(837.2889404296875, 99.98998260498047, 2270.99658203125)
end)

Tab7Section:NewButton("Police Room", "Teleports to to the Police Room", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(836.5386352539062, 99.98998260498047, 2320.604248046875)
end)
            
Tab7Section:NewButton("Cafeteria", "Teleports you to the Cafeteria!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(918.994873046875, 99.98993682861328, 2325.73095703125)
end)
   
Tab7Section:NewButton("Criminal Base Inside", "Teleports you to the Criminal Base Inside!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-975.8451538085938, 109.32379150390625, 2053.11376953125)
end)

Tab7Section:NewButton("Prison Cells", "Teleports You to the Prison Cells!", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(919.5551147460938, 99.98998260498047, 2441.700927734375)
end)

Tab8Section:NewToggle("Auto Tap", "", function(state)
    if state then
while true do
local A_1 = "Tapping"
local Event = game:GetService("ReplicatedStorage").Remotes.Tapping
Event:FireServer(A_1)
wait(0)
end
    else
game:GetService'TeleportService':TeleportToPlaceInstance(game.PlaceId,game.JobId,game:GetService'Players'.LocalPlayer)
    end
end)

Tab8Section:NewToggle("Auto Training", "", function(state)
    if state then
while true do
local A_2 = game:GetService("Workspace")["__WORKSPACE"]["__Interact"].Training
local Event = game:GetService("ReplicatedStorage").Remotes.Training
Event:FireServer(A_1, A_2)
wait(1)
end
    else
game:GetService'TeleportService':TeleportToPlaceInstance(game.PlaceId,game.JobId,game:GetService'Players'.LocalPlayer)
    end
end)

Tab9Section:NewToggle("Auto Eat", "", function(bool)
_G.d = bool
while _G.d do wait()
for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
      if v.Name == "swing" then
      game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
    end
    end
game:GetService'VirtualUser':Button1Down(Vector2.new(1,1))
end
end)

Tab9Section:NewToggle("Auto Sell", "", function(bool)

_G.x = bool

while _G.x do wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(16.686979293823, 11.525447845459, -6.6648082733154) -- Change this teleport to island if u want
wait(2)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-25.561155319214, -1.3697438240051, -6.9260401725769)
wait(2)
end
end)

local Tab9Section = Tab9:NewSection("AutoBuy")

Tab9Section:NewToggle("Auto Buy Food", "", function(bool)
_G.z = bool

while _G.z do wait()
    -- Auto Buy Food

local args = {
    [1] = "Bats"
}

game:GetService("ReplicatedStorage").Knit.Services.ShopService.RE.buyAll:FireServer(unpack(args))

    end
end)

Tab9Section:NewToggle("Auto Buy DNA", "", function(bool)
_G.f = bool

while _G.f do wait()
-- Auto Buy DNA

local args = {
    [1] = "DNA"
}

game:GetService("ReplicatedStorage").Knit.Services.ShopService.RE.buyAll:FireServer(unpack(args))

    end
end)

local Tab9Section = Tab9:NewSection("Egg")
Selected = ""
Eggs = {}
for i,v in pairs(game:GetService("ReplicatedStorage").Eggs:GetChildren()) do
    table.insert(Eggs,v.Name)
end

Tab9Section:NewDropdown("Selected Players", "DropdownInf", players, function(dd)
    Selected = dd
end)

local Tab9Section = Tab9:NewSection("Misc")

Tab9Section:NewToggle("Anti AFK", "", function(bool)
    _G.t = bool
    while _G.t do wait()
        local bb=game:service'VirtualUser'
            bb:CaptureController()
            bb:ClickButton2(Vector2.new())
    end
end)
end)

local Tab10Section = Tab10:NewSection("Fire Hub [3]")

Tab10Section:NewButton("Fire Hub [3]", "", function()
local message = Instance.new("Message",workspace) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1) 

message.Text = "Loading..." 

wait(1) 

message.Text = "Loading" 

wait(1) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1) 

message.Text = "Loading..." 

wait(1) 

message.Text = "Loading" 

wait(1) 

message.Text = "Loading." 

wait(1) 

message.Text = "Loading.." 

wait(1.8) 

message:Destroy()
local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Fire Hub [3]", "BloodTheme")

local Tab1 = Window:NewTab("SwordMan Simulator")
local Tab1Section = Tab1:NewSection("SwordMan Simulator")

Tab1Section:NewToggle("Auto Equip Tool", "", function(state)
    if state then
getgenv().autoEQ = true
while getgenv().autoEQ == true do
for i,tools in pairs(game.Players.LocalPlayer.Backpack:GetDescendants()) do
		if tools:IsA("Tool") then
			tools.Parent = game.Players.LocalPlayer.Character
		end
	end
wait(0.1)
end
    else
getgenv().autoEQ = false
    end
end)

Tab1Section:NewButton("Auto Click", "", function()
local range = 1000

local player = game:GetService("Players").LocalPlayer

game:GetService("RunService").RenderStepped:Connect(function()
    local p = game.Players:GetPlayers()
    for i = 2, #p do local v = p[i].Character
        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and player:DistanceFromCharacter(v.HumanoidRootPart.Position) <= range then
            local tool = player.Character and player.Character:FindFirstChildOfClass("Tool")
            if tool and tool:FindFirstChild("Handle") then
                tool:Activate()
                for i,v in next, v:GetChildren() do
                    if v:IsA("BasePart") then
                        firetouchinterest(tool.Handle,v,0)
                        firetouchinterest(tool.Handle,v,1)
                    end
                end
            end
        end
    end
end)
end)

Tab2Section:NewButton("Auto Click", "", function()
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Sell" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait()
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "Sell" then
         	child.CFrame = CFrame.new(-144, -34, -2)
         	end
end
end)

Tab1Section:NewButton("Open Rune Shop", "", function()
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "RuneShop" then
         	child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		end
  	end
wait()
local children = game.Workspace:GetChildren()
	for _, child in pairs(children) do
  		for _, child in pairs(child:GetChildren()) do
       		table.insert(children, child)
  		 end
  		 if child:IsA("BasePart") and child.Name == "RuneShop" then
         	child.CFrame = CFrame.new(-101, -34, -15)
		end
  	end
end)

local Tab1Section = Tab1:NewSection("Boss Teleport")

Tab1Section:NewButton("Noob Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1539, 3, 810)
end)

Tab1Section:NewButton("Knight Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1558, 3, 24)
end)

Tab1Section:NewButton("Orc Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1685, 3, -1016)
end)

Tab1Section:NewButton("Wizzard Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-349, 3, -2881)
end)

Tab1Section:NewButton("Pirate Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1870, 3, -2619)
end)

Tab1Section:NewButton("Ninja Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-1673, 6, 1572)
end)

Tab1Section:NewButton("Undead Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-842, 6, 2495)
end)

Tab1Section:NewButton("Ice King Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(422, 6, 2505)
end)

Tab1Section:NewButton("Zeus Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(2116, 3, 1010)
end)

Tab1Section:NewButton("Black Knight Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(2022, 6, 2253)
end)

Tab1Section:NewButton("Reaper Boss", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(1862, 6, 3758)
end)


local Tab1Section = Tab1:NewSection("Teretory")

Tab1Section:NewButton("Territory 1", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(114, -34, -62)
end)

Tab1Section:NewButton("Territory 2", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-84, 50, 6059)
end)

Tab1Section:NewButton("Territory 3", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(130, -34, 193)
end)

Tab1Section:NewButton("King Territory", "", function()
game.Players.LocalPlayer.Character.Humanoid.RootPart.CFrame = CFrame.new(-283, 23, 106)
end)
end)

local Tab10Section = Tab10:NewSection("Vhub")

Tab10Section:NewButton("Vhub", "", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/itsyaboivincentt5315/script/main/VHub.txt'),true))()
end)

local Tab10Section = Tab10:NewSection("Moon Ui")

Tab10Section:NewButton("Moon Ui", "", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)

local Tab10Section = Tab10:NewSection("Bobo Hub")

Tab10Section:NewButton("Bobo Hub", "", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ItsRhylee/Rhylee/main/It's%20Rhylee%20Hub%20(Beta)"))()
end)

local Tab10Section = Tab10:NewSection("Pro Hub")

Tab10Section:NewButton("Pro Hub", "", function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Kindasua/v.1-beta/main/Fixed%20bugs%20v.1%20beta"), true))()
end)
