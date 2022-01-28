-- Hacked by nobody
local AdminMenuViown = Instance.new("ScreenGui")
local MainGUI = Instance.new("Frame")
local Top = Instance.new("Frame")
local General = Instance.new("TextButton")
local TopText = Instance.new("TextLabel")
local ID = Instance.new("TextLabel")
local Version = Instance.new("TextLabel")
local LocalPlayer = Instance.new("TextButton")
local Scripts = Instance.new("TextButton")
local Settings = Instance.new("TextButton")
local X_Shadow = Instance.new("TextButton")
local X = Instance.new("TextButton")
local Executor = Instance.new("Frame")
local Top_2 = Instance.new("Frame")
local Code = Instance.new("TextBox")
local Execute = Instance.new("TextButton")
local Clear = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local General_2 = Instance.new("Frame")
local Shattervast = Instance.new("TextButton")
local ExecutorLoader = Instance.new("TextButton")
local InfiniteYield = Instance.new("TextButton")
local N3xulis = Instance.new("TextButton")
local AdminScripts = Instance.new("TextLabel")
local FEScripts = Instance.new("TextLabel")
local From_GUI = Instance.new("TextLabel")
local TrollGUI = Instance.new("TextButton")
local MusicPlayer = Instance.new("TextButton")
local ScrollingFrame = Instance.new("ScrollingFrame")
local FEFlingKill = Instance.new("TextButton")
local FEHax1337 = Instance.new("TextButton")
local FEShutdown = Instance.new("TextButton")
local PhantomForces = Instance.new("TextButton")
local MadCity = Instance.new("TextButton")
local MadCityAutofarm = Instance.new("TextButton")
local SlayingSimulator = Instance.new("TextButton")
local DashingSimulator = Instance.new("TextButton")
local ChatBypass = Instance.new("TextButton")
local Credits = Instance.new("Frame")
local Credit = Instance.new("TextLabel")
local Scripts_2 = Instance.new("Frame")
local ScriptsScroll = Instance.new("ScrollingFrame")
local Script = Instance.new("TextButton")
local Script_2 = Instance.new("TextButton")
local Script_3 = Instance.new("TextButton")
local Script_4 = Instance.new("TextButton")
local Script_5 = Instance.new("TextButton")
local Script_6 = Instance.new("TextButton")
local Script_7 = Instance.new("TextButton")
local Script_8 = Instance.new("TextButton")
local Script_9 = Instance.new("TextButton")
local Settings_2 = Instance.new("Frame")
local DarkMode = Instance.new("TextButton")
local toggle = Instance.new("TextLabel")
local Size = Instance.new("TextBox")
local Change = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local RainbowTopBar = Instance.new("TextButton")
local DFeatures = Instance.new("TextBox")
local Load = Instance.new("TextButton")
local LocalPlayer_2 = Instance.new("Frame")
local Fire = Instance.new("TextButton")
local Sparkes = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local Walkspeed = Instance.new("TextButton")
local JumpPower = Instance.new("TextButton")
local Gravity = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local FEInvisible = Instance.new("TextButton")
local god = Instance.new("TextButton")
local LoginGUI = Instance.new("ImageLabel")
local Login = Instance.new("TextBox")
local TextLabel_2 = Instance.new("TextLabel")
local Password = Instance.new("TextBox")
local TextLabel_3 = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local Access = Instance.new("TextButton")
local ForgotPassword = Instance.new("TextButton")
local Info = Instance.new("ImageLabel")
local TextLabel_4 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local Top_3 = Instance.new("ImageLabel")
local TopText_2 = Instance.new("TextLabel")
local Spin = Instance.new("ImageLabel")
local TextHit = Instance.new("TextLabel")
--Properties:
AdminMenuViown.Name = "Admin Menu ~ Viown"
AdminMenuViown.Parent = game.CoreGui
AdminMenuViown.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainGUI.Name = "MainGUI"
MainGUI.Parent = AdminMenuViown
MainGUI.Active = true
MainGUI.BackgroundColor3 = Color3.new(1, 1, 1)
MainGUI.BorderSizePixel = 0
MainGUI.Position = UDim2.new(0.203718647, 0, 0.234113723, 0)
MainGUI.Selectable = true
MainGUI.Size = UDim2.new(0, 690, 0, 363)
MainGUI.Visible = false

Top.Name = "Top"
Top.Parent = MainGUI
Top.BackgroundColor3 = Color3.new(0.278431, 0.470588, 1)
Top.BorderSizePixel = 0
Top.Size = UDim2.new(0, 690, 0, 100)

General.Name = "General"
General.Parent = Top
General.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
General.BorderSizePixel = 0
General.ClipsDescendants = true
General.Position = UDim2.new(0.147845462, -100, 0.743168056, -25)
General.Size = UDim2.new(0, 169, 0, 50)
General.AutoButtonColor = false
General.Font = Enum.Font.SourceSansLight
General.Text = "General"
General.TextColor3 = Color3.new(1, 1, 1)
General.TextSize = 18

TopText.Name = "TopText"
TopText.Parent = Top
TopText.BackgroundColor3 = Color3.new(0.345098, 0.356863, 1)
TopText.BorderSizePixel = 0
TopText.Position = UDim2.new(0.0029179228, 0, 0, 0)
TopText.Size = UDim2.new(0, 688, 0, 50)
TopText.Font = Enum.Font.SourceSansLight
TopText.Text = "   Reign Admin Menu"
TopText.TextColor3 = Color3.new(0.270588, 0.964706, 1)
TopText.TextScaled = true
TopText.TextSize = 14
TopText.TextWrapped = true
TopText.TextXAlignment = Enum.TextXAlignment.Left

ID.Name = "ID"
ID.Parent = TopText
ID.BackgroundColor3 = Color3.new(1, 1, 1)
ID.BackgroundTransparency = 1
ID.Position = UDim2.new(0.563953578, 0, 0, 0)
ID.Size = UDim2.new(0, 260, 0, 50)
ID.Font = Enum.Font.SourceSansLight
ID.Text = "Hello, [Player], ID = 0"
ID.TextColor3 = Color3.new(0.992157, 1, 0.360784)
ID.TextScaled = true
ID.TextSize = 14
ID.TextWrapped = true

Version.Name = "Version"
Version.Parent = TopText
Version.BackgroundColor3 = Color3.new(1, 1, 1)
Version.BackgroundTransparency = 1
Version.Position = UDim2.new(0.491279066, 0, 0, 0)
Version.Rotation = -18
Version.Size = UDim2.new(0, 50, 0, 50)
Version.Font = Enum.Font.Cartoon
Version.Text = "V1.6.5"
Version.TextColor3 = Color3.new(1, 1, 1)
Version.TextScaled = true
Version.TextSize = 14
Version.TextStrokeTransparency = 0
Version.TextWrapped = true

LocalPlayer.Name = "LocalPlayer"
LocalPlayer.Parent = Top
LocalPlayer.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
LocalPlayer.BorderSizePixel = 0
LocalPlayer.ClipsDescendants = true
LocalPlayer.Position = UDim2.new(0.392773002, -100, 0.743168056, -25)
LocalPlayer.Size = UDim2.new(0, 169, 0, 50)
LocalPlayer.AutoButtonColor = false
LocalPlayer.Font = Enum.Font.SourceSansLight
LocalPlayer.Text = "LocalPlayer"
LocalPlayer.TextColor3 = Color3.new(1, 1, 1)
LocalPlayer.TextSize = 18

Scripts.Name = "Scripts"
Scripts.Parent = Top
Scripts.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
Scripts.BorderSizePixel = 0
Scripts.ClipsDescendants = true
Scripts.Position = UDim2.new(0.637700558, -100, 0.743168056, -25)
Scripts.Size = UDim2.new(0, 169, 0, 50)
Scripts.AutoButtonColor = false
Scripts.Font = Enum.Font.SourceSansLight
Scripts.Text = "Scripts"
Scripts.TextColor3 = Color3.new(1, 1, 1)
Scripts.TextSize = 18

Settings.Name = "Settings"
Settings.Parent = Top
Settings.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
Settings.BorderSizePixel = 0
Settings.ClipsDescendants = true
Settings.Position = UDim2.new(0.882628083, -100, 0.743168056, -25)
Settings.Size = UDim2.new(0, 181, 0, 50)
Settings.AutoButtonColor = false
Settings.Font = Enum.Font.SourceSansLight
Settings.Text = "Settings"
Settings.TextColor3 = Color3.new(1, 1, 1)
Settings.TextSize = 18

X_Shadow.Name = "X_Shadow"
X_Shadow.Parent = Top
X_Shadow.BackgroundColor3 = Color3.new(1, 1, 1)
X_Shadow.BackgroundTransparency = 1
X_Shadow.Position = UDim2.new(0.959439754, 0, 0, 0)
X_Shadow.Size = UDim2.new(0, 28, 0, 50)
X_Shadow.Font = Enum.Font.SourceSansBold
X_Shadow.Text = "X"
X_Shadow.TextColor3 = Color3.new(0, 0, 0)
X_Shadow.TextScaled = true
X_Shadow.TextSize = 14
X_Shadow.TextTransparency = 0.5
X_Shadow.TextWrapped = true

X.Name = "X"
X.Parent = Top
X.BackgroundColor3 = Color3.new(1, 1, 1)
X.BackgroundTransparency = 1
X.Position = UDim2.new(0.957990468, 0, -0.0100000016, 0)
X.Size = UDim2.new(0, 28, 0, 50)
X.Font = Enum.Font.SourceSansBold
X.Text = "X"
X.TextColor3 = Color3.new(0.905882, 0.129412, 0.129412)
X.TextScaled = true
X.TextSize = 14
X.TextWrapped = true

Executor.Name = "Executor"
Executor.Parent = MainGUI
Executor.Active = true
Executor.BackgroundColor3 = Color3.new(0.34902, 0.521569, 1)
Executor.BackgroundTransparency = 0.5
Executor.BorderSizePixel = 0
Executor.Position = UDim2.new(-0.347826093, 0, -0.0385674946, 0)
Executor.Selectable = true
Executor.Size = UDim2.new(0, 456, 0, 227)
Executor.Visible = false

Top_2.Name = "Top"
Top_2.Parent = Executor
Top_2.BackgroundColor3 = Color3.new(0.270588, 0.305882, 0.776471)
Top_2.BackgroundTransparency = 0.5
Top_2.BorderSizePixel = 0
Top_2.Size = UDim2.new(0, 456, 0, 14)

Code.Name = "Code"
Code.Parent = Executor
Code.BackgroundColor3 = Color3.new(0.219608, 0.258824, 1)
Code.BackgroundTransparency = 0.5
Code.BorderSizePixel = 0
Code.Position = UDim2.new(0.0350877196, 0, 0.114537448, 0)
Code.Size = UDim2.new(0, 426, 0, 152)
Code.SizeConstraint = Enum.SizeConstraint.RelativeYY
Code.ClearTextOnFocus = false
Code.Font = Enum.Font.SourceSans
Code.Text = ""
Code.TextColor3 = Color3.new(1, 1, 1)
Code.TextSize = 14
Code.TextXAlignment = Enum.TextXAlignment.Left
Code.TextYAlignment = Enum.TextYAlignment.Top

Execute.Name = "Execute"
Execute.Parent = Executor
Execute.BackgroundColor3 = Color3.new(0.356863, 0.309804, 1)
Execute.BackgroundTransparency = 0.5
Execute.BorderSizePixel = 0
Execute.Position = UDim2.new(0.0570175499, 0, 0.814977944, 0)
Execute.Size = UDim2.new(0, 145, 0, 35)
Execute.Font = Enum.Font.SourceSansLight
Execute.Text = "Execute"
Execute.TextColor3 = Color3.new(0, 0, 0)
Execute.TextScaled = true
Execute.TextSize = 14
Execute.TextWrapped = true

Clear.Name = "Clear"
Clear.Parent = Executor
Clear.BackgroundColor3 = Color3.new(0.356863, 0.309804, 1)
Clear.BackgroundTransparency = 0.5
Clear.BorderSizePixel = 0
Clear.Position = UDim2.new(0.427631587, 0, 0.814977944, 0)
Clear.Size = UDim2.new(0, 145, 0, 35)
Clear.Font = Enum.Font.SourceSansLight
Clear.Text = "Clear"
Clear.TextColor3 = Color3.new(0, 0, 0)
Clear.TextScaled = true
Clear.TextSize = 14
Clear.TextWrapped = true

Close.Name = "Close"
Close.Parent = Executor
Close.BackgroundColor3 = Color3.new(0.356863, 0.309804, 1)
Close.BackgroundTransparency = 0.5
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.796052635, 0, 0.814977944, 0)
Close.Size = UDim2.new(0, 71, 0, 35)
Close.Font = Enum.Font.SourceSansLight
Close.Text = "Close"
Close.TextColor3 = Color3.new(0, 0, 0)
Close.TextScaled = true
Close.TextSize = 14
Close.TextWrapped = true

General_2.Name = "General"
General_2.Parent = MainGUI
General_2.BackgroundColor3 = Color3.new(1, 1, 1)
General_2.BackgroundTransparency = 1
General_2.BorderSizePixel = 0
General_2.Position = UDim2.new(0, 0, 0.272727281, 0)
General_2.Size = UDim2.new(0, 690, 0, 264)
General_2.Visible = false

Shattervast.Name = "Shattervast"
Shattervast.Parent = General_2
Shattervast.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
Shattervast.BorderSizePixel = 0
Shattervast.ClipsDescendants = true
Shattervast.Position = UDim2.new(0.882628083, -100, 0.869087219, -25)
Shattervast.Size = UDim2.new(0, 169, 0, 47)
Shattervast.AutoButtonColor = false
Shattervast.Font = Enum.Font.SourceSansLight
Shattervast.Text = "Shattervast"
Shattervast.TextColor3 = Color3.new(1, 1, 1)
Shattervast.TextSize = 18

ExecutorLoader.Name = "ExecutorLoader"
ExecutorLoader.Parent = General_2
ExecutorLoader.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
ExecutorLoader.BorderSizePixel = 0
ExecutorLoader.ClipsDescendants = true
ExecutorLoader.Position = UDim2.new(0.169584632, -100, 0.348484844, -25)
ExecutorLoader.Size = UDim2.new(0, 169, 0, 51)
ExecutorLoader.AutoButtonColor = false
ExecutorLoader.Font = Enum.Font.SourceSansLight
ExecutorLoader.Text = "In-Game Executor"
ExecutorLoader.TextColor3 = Color3.new(1, 1, 1)
ExecutorLoader.TextSize = 18

InfiniteYield.Name = "Infinite Yield"
InfiniteYield.Parent = General_2
InfiniteYield.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
InfiniteYield.BorderSizePixel = 0
InfiniteYield.ClipsDescendants = true
InfiniteYield.Position = UDim2.new(0.882628083, -100, 0.348484844, -25)
InfiniteYield.Size = UDim2.new(0, 169, 0, 51)
InfiniteYield.AutoButtonColor = false
InfiniteYield.Font = Enum.Font.SourceSansLight
InfiniteYield.Text = "Infinite Yield"
InfiniteYield.TextColor3 = Color3.new(1, 1, 1)
InfiniteYield.TextSize = 18

N3xulis.Name = "N3xulis"
N3xulis.Parent = General_2
N3xulis.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
N3xulis.BorderSizePixel = 0
N3xulis.ClipsDescendants = true
N3xulis.Position = UDim2.new(0.882628083, -100, 0.609902382, -25)
N3xulis.Size = UDim2.new(0, 169, 0, 54)
N3xulis.AutoButtonColor = false
N3xulis.Font = Enum.Font.SourceSansLight
N3xulis.Text = "N3xulis"
N3xulis.TextColor3 = Color3.new(1, 1, 1)
N3xulis.TextSize = 18

AdminScripts.Name = "Admin Scripts"
AdminScripts.Parent = General_2
AdminScripts.BackgroundColor3 = Color3.new(1, 1, 1)
AdminScripts.BackgroundTransparency = 1
AdminScripts.Position = UDim2.new(0.70869565, 0, 0.0037878789, 0)
AdminScripts.Size = UDim2.new(0, 200, 0, 72)
AdminScripts.Font = Enum.Font.SourceSansLight
AdminScripts.Text = "Admin Scripts:"
AdminScripts.TextColor3 = Color3.new(0.345098, 0.470588, 0.815686)
AdminScripts.TextScaled = true
AdminScripts.TextSize = 14
AdminScripts.TextWrapped = true

FEScripts.Name = "FE Scripts"
FEScripts.Parent = General_2
FEScripts.BackgroundColor3 = Color3.new(1, 1, 1)
FEScripts.BackgroundTransparency = 1
FEScripts.Position = UDim2.new(0.355072469, 0, -0.0454545468, 0)
FEScripts.Size = UDim2.new(0, 200, 0, 63)
FEScripts.Font = Enum.Font.SourceSansLight
FEScripts.Text = "FE Scripts:"
FEScripts.TextColor3 = Color3.new(0.345098, 0.470588, 0.815686)
FEScripts.TextScaled = true
FEScripts.TextSize = 14
FEScripts.TextWrapped = true

From_GUI.Name = "From_GUI"
From_GUI.Parent = General_2
From_GUI.BackgroundColor3 = Color3.new(1, 1, 1)
From_GUI.BackgroundTransparency = 1
From_GUI.Position = UDim2.new(0.00289850659, 0, 0, 0)
From_GUI.Size = UDim2.new(0, 200, 0, 72)
From_GUI.Font = Enum.Font.SourceSansLight
From_GUI.Text = "From this GUI:"
From_GUI.TextColor3 = Color3.new(0.345098, 0.470588, 0.815686)
From_GUI.TextScaled = true
From_GUI.TextSize = 14
From_GUI.TextWrapped = true

TrollGUI.Name = "Troll GUI"
TrollGUI.Parent = General_2
TrollGUI.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
TrollGUI.BorderSizePixel = 0
TrollGUI.ClipsDescendants = true
TrollGUI.Position = UDim2.new(0.169584632, -100, 0.609902382, -25)
TrollGUI.Size = UDim2.new(0, 169, 0, 51)
TrollGUI.AutoButtonColor = false
TrollGUI.Font = Enum.Font.SourceSansLight
TrollGUI.Text = "Troll GUI"
TrollGUI.TextColor3 = Color3.new(1, 1, 1)
TrollGUI.TextSize = 18

MusicPlayer.Name = "MusicPlayer"
MusicPlayer.Parent = General_2
MusicPlayer.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
MusicPlayer.BorderSizePixel = 0
MusicPlayer.ClipsDescendants = true
MusicPlayer.Position = UDim2.new(0.169584632, -100, 0.869087219, -25)
MusicPlayer.Size = UDim2.new(0, 169, 0, 47)
MusicPlayer.AutoButtonColor = false
MusicPlayer.Font = Enum.Font.SourceSansLight
MusicPlayer.Text = "Music Player"
MusicPlayer.TextColor3 = Color3.new(1, 1, 1)
MusicPlayer.TextSize = 18

ScrollingFrame.Parent = General_2
ScrollingFrame.BackgroundColor3 = Color3.new(0.380392, 0.45098, 0.862745)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.330434769, 0, 0.166666672, 0)
ScrollingFrame.Size = UDim2.new(0, 244, 0, 207)
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 4, 0)

FEFlingKill.Name = "FE Fling/Kill"
FEFlingKill.Parent = ScrollingFrame
FEFlingKill.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
FEFlingKill.BorderSizePixel = 0
FEFlingKill.ClipsDescendants = true
FEFlingKill.Position = UDim2.new(0.562742233, -100, 0.0454545505, -25)
FEFlingKill.Size = UDim2.new(0, 169, 0, 51)
FEFlingKill.AutoButtonColor = false
FEFlingKill.Font = Enum.Font.SourceSansLight
FEFlingKill.Text = "FE Fling/Kill"
FEFlingKill.TextColor3 = Color3.new(1, 1, 1)
FEFlingKill.TextSize = 18

FEHax1337.Name = "FE Hax 1337"
FEHax1337.Parent = ScrollingFrame
FEHax1337.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
FEHax1337.BorderSizePixel = 0
FEHax1337.ClipsDescendants = true
FEHax1337.Position = UDim2.new(0.560093164, -100, 0.109902367, -25)
FEHax1337.Size = UDim2.new(0, 169, 0, 54)
FEHax1337.AutoButtonColor = false
FEHax1337.Font = Enum.Font.SourceSansLight
FEHax1337.Text = "FE Hax 1337"
FEHax1337.TextColor3 = Color3.new(1, 1, 1)
FEHax1337.TextSize = 18

FEShutdown.Name = "FE Shutdown"
FEShutdown.Parent = ScrollingFrame
FEShutdown.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
FEShutdown.BorderSizePixel = 0
FEShutdown.ClipsDescendants = true
FEShutdown.Position = UDim2.new(0.560000002, -100, 0.177477255, -25)
FEShutdown.Size = UDim2.new(0, 169, 0, 47)
FEShutdown.AutoButtonColor = false
FEShutdown.Font = Enum.Font.SourceSansLight
FEShutdown.Text = "FE Shutdown"
FEShutdown.TextColor3 = Color3.new(1, 1, 1)
FEShutdown.TextSize = 18

PhantomForces.Name = "Phantom Forces"
PhantomForces.Parent = ScrollingFrame
PhantomForces.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
PhantomForces.BorderSizePixel = 0
PhantomForces.ClipsDescendants = true
PhantomForces.Position = UDim2.new(0.559999943, -100, 0.23997727, -25)
PhantomForces.Size = UDim2.new(0, 169, 0, 47)
PhantomForces.AutoButtonColor = false
PhantomForces.Font = Enum.Font.SourceSansLight
PhantomForces.Text = "Phantom Forces Script"
PhantomForces.TextColor3 = Color3.new(1, 1, 1)
PhantomForces.TextSize = 18

MadCity.Name = "Mad City"
MadCity.Parent = ScrollingFrame
MadCity.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
MadCity.BorderSizePixel = 0
MadCity.ClipsDescendants = true
MadCity.Position = UDim2.new(0.560000002, -100, 0.29490146, -25)
MadCity.Size = UDim2.new(0, 169, 0, 47)
MadCity.AutoButtonColor = false
MadCity.Font = Enum.Font.SourceSansLight
MadCity.Text = "Mad City Script"
MadCity.TextColor3 = Color3.new(1, 1, 1)
MadCity.TextSize = 18

MadCityAutofarm.Name = "Mad City Autofarm"
MadCityAutofarm.Parent = ScrollingFrame
MadCityAutofarm.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
MadCityAutofarm.BorderSizePixel = 0
MadCityAutofarm.ClipsDescendants = true
MadCityAutofarm.Position = UDim2.new(0.57229507, -100, 0.358348429, -25)
MadCityAutofarm.Size = UDim2.new(0, 169, 0, 47)
MadCityAutofarm.AutoButtonColor = false
MadCityAutofarm.Font = Enum.Font.SourceSansLight
MadCityAutofarm.Text = "Mad City XP Autofarm"
MadCityAutofarm.TextColor3 = Color3.new(1, 1, 1)
MadCityAutofarm.TextSize = 18

SlayingSimulator.Name = "Slaying Simulator"
SlayingSimulator.Parent = ScrollingFrame
SlayingSimulator.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
SlayingSimulator.BorderSizePixel = 0
SlayingSimulator.ClipsDescendants = true
SlayingSimulator.Position = UDim2.new(0.57229507, -100, 0.423689336, -25)
SlayingSimulator.Size = UDim2.new(0, 169, 0, 47)
SlayingSimulator.AutoButtonColor = false
SlayingSimulator.Font = Enum.Font.SourceSansLight
SlayingSimulator.Text = "Slaying Simulator"
SlayingSimulator.TextColor3 = Color3.new(1, 1, 1)
SlayingSimulator.TextSize = 18

DashingSimulator.Name = "Dashing Simulator"
DashingSimulator.Parent = ScrollingFrame
DashingSimulator.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
DashingSimulator.BorderSizePixel = 0
DashingSimulator.ClipsDescendants = true
DashingSimulator.Position = UDim2.new(0.57229507, -100, 0.477666616, -25)
DashingSimulator.Size = UDim2.new(0, 169, 0, 47)
DashingSimulator.AutoButtonColor = false
DashingSimulator.Font = Enum.Font.SourceSansLight
DashingSimulator.Text = "Dashing Simulator"
DashingSimulator.TextColor3 = Color3.new(1, 1, 1)
DashingSimulator.TextSize = 18

ChatBypass.Name = "Chat Bypass"
ChatBypass.Parent = ScrollingFrame
ChatBypass.BackgroundColor3 = Color3.new(0.262745, 0.596078, 1)
ChatBypass.BorderSizePixel = 0
ChatBypass.ClipsDescendants = true
ChatBypass.Position = UDim2.new(0.57229507, -100, 0.536378682, -25)
ChatBypass.Size = UDim2.new(0, 169, 0, 47)
ChatBypass.AutoButtonColor = false
ChatBypass.Font = Enum.Font.SourceSansLight
ChatBypass.Text = "Chat Bypass (do /e [message])"
ChatBypass.TextColor3 = Color3.new(1, 1, 1)
ChatBypass.TextSize = 18

Credits.Name = "Credits"
Credits.Parent = MainGUI
Credits.BackgroundColor3 = Color3.new(1, 1, 1)
Credits.BackgroundTransparency = 1
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0, 0, 0.272727281, 0)
Credits.Size = UDim2.new(0, 690, 0, 264)

Credit.Name = "Credit"
Credit.Parent = Credits
Credit.BackgroundColor3 = Color3.new(1, 1, 1)
Credit.BackgroundTransparency = 1
Credit.Position = UDim2.new(0.00144927541, 0, 0.00378787518, 0)
Credit.Size = UDim2.new(0, 690, 0, 264)
Credit.Font = Enum.Font.SourceSansLight
Credit.Text = "This Menu was created by Viown, any problems experienced add me on discord: vi#9292"
Credit.TextColor3 = Color3.new(0.215686, 0.254902, 0.631373)
Credit.TextScaled = true
Credit.TextSize = 14
Credit.TextWrapped = true

Scripts_2.Name = "Scripts"
Scripts_2.Parent = MainGUI
Scripts_2.BackgroundColor3 = Color3.new(1, 1, 1)
Scripts_2.BorderSizePixel = 0
Scripts_2.Position = UDim2.new(0, 0, 0.272727281, 0)
Scripts_2.Size = UDim2.new(0, 689, 0, 264)
Scripts_2.Visible = false

ScriptsScroll.Name = "ScriptsScroll"
ScriptsScroll.Parent = Scripts_2
ScriptsScroll.BackgroundColor3 = Color3.new(0.941177, 0.941177, 0.941177)
ScriptsScroll.BackgroundTransparency = 1
ScriptsScroll.BorderSizePixel = 0
ScriptsScroll.Size = UDim2.new(0, 689, 0, 264)

Script.Name = "Script"
Script.Parent = ScriptsScroll
Script.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script.BorderSizePixel = 0
Script.Size = UDim2.new(0, 662, 0, 26)
Script.Font = Enum.Font.SourceSansBold
Script.Text = "Updated Chat Bypass ~ Ieoanhalt123"
Script.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script.TextScaled = true
Script.TextSize = 14
Script.TextWrapped = true

Script_2.Name = "Script"
Script_2.Parent = ScriptsScroll
Script_2.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_2.BorderSizePixel = 0
Script_2.Position = UDim2.new(0, 0, 0.0492424257, 0)
Script_2.Size = UDim2.new(0, 662, 0, 26)
Script_2.Font = Enum.Font.SourceSansBold
Script_2.Text = "Dashing Simulator ~  reavreav"
Script_2.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_2.TextScaled = true
Script_2.TextSize = 14
Script_2.TextWrapped = true

Script_3.Name = "Script"
Script_3.Parent = ScriptsScroll
Script_3.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_3.BorderSizePixel = 0
Script_3.Position = UDim2.new(0, 0, 0.0984848514, 0)
Script_3.Size = UDim2.new(0, 662, 0, 26)
Script_3.Font = Enum.Font.SourceSansBold
Script_3.Text = "Lumber Tycoon ~ kintol2005"
Script_3.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_3.TextScaled = true
Script_3.TextSize = 14
Script_3.TextWrapped = true

Script_4.Name = "Script"
Script_4.Parent = ScriptsScroll
Script_4.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_4.BorderSizePixel = 0
Script_4.Position = UDim2.new(0, 0, 0.147727281, 0)
Script_4.Size = UDim2.new(0, 662, 0, 26)
Script_4.Font = Enum.Font.SourceSansBold
Script_4.Text = "OP Gui! ~ Corewave"
Script_4.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_4.TextScaled = true
Script_4.TextSize = 14
Script_4.TextWrapped = true

Script_5.Name = "Script"
Script_5.Parent = ScriptsScroll
Script_5.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_5.BorderSizePixel = 0
Script_5.Position = UDim2.new(0, 0, 0.196969703, 0)
Script_5.Size = UDim2.new(0, 662, 0, 26)
Script_5.Font = Enum.Font.SourceSansBold
Script_5.Text = "Zertex GUI ~ Jayden A"
Script_5.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_5.TextScaled = true
Script_5.TextSize = 14
Script_5.TextWrapped = true

Script_6.Name = "Script"
Script_6.Parent = ScriptsScroll
Script_6.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_6.BorderSizePixel = 0
Script_6.Position = UDim2.new(0, 0, 0.246212125, 0)
Script_6.Size = UDim2.new(0, 662, 0, 26)
Script_6.Font = Enum.Font.SourceSansBold
Script_6.Text = "Northern Frontier GUI ~ Unknown"
Script_6.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_6.TextScaled = true
Script_6.TextSize = 14
Script_6.TextWrapped = true

Script_7.Name = "Script"
Script_7.Parent = ScriptsScroll
Script_7.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_7.BorderSizePixel = 0
Script_7.Position = UDim2.new(0, 0, 0.295454562, 0)
Script_7.Size = UDim2.new(0, 662, 0, 26)
Script_7.Font = Enum.Font.SourceSansBold
Script_7.Text = "Prison Life FE Gui ~ Racist Dolphin"
Script_7.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_7.TextScaled = true
Script_7.TextSize = 14
Script_7.TextWrapped = true

Script_8.Name = "Script"
Script_8.Parent = ScriptsScroll
Script_8.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_8.BorderSizePixel = 0
Script_8.Position = UDim2.new(0, 0, 0.344696999, 0)
Script_8.Size = UDim2.new(0, 662, 0, 26)
Script_8.Font = Enum.Font.SourceSansBold
Script_8.Text = "[Synapse] Hospital Life 2 FE Gear GUI ~ albie368"
Script_8.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_8.TextScaled = true
Script_8.TextSize = 14
Script_8.TextWrapped = true

Script_9.Name = "Script"
Script_9.Parent = ScriptsScroll
Script_9.BackgroundColor3 = Color3.new(0.478431, 0.439216, 1)
Script_9.BorderSizePixel = 0
Script_9.Position = UDim2.new(0, 0, 0.393939435, 0)
Script_9.Size = UDim2.new(0, 662, 0, 26)
Script_9.Font = Enum.Font.SourceSansBold
Script_9.Text = "[Paid Exploit] Katie's FE Gui ~ Katie"
Script_9.TextColor3 = Color3.new(0.207843, 0.27451, 0.631373)
Script_9.TextScaled = true
Script_9.TextSize = 14
Script_9.TextWrapped = true

Settings_2.Name = "Settings"
Settings_2.Parent = MainGUI
Settings_2.BackgroundColor3 = Color3.new(1, 1, 1)
Settings_2.BorderSizePixel = 0
Settings_2.Position = UDim2.new(0, 0, 0.275482088, 0)
Settings_2.Size = UDim2.new(0, 689, 0, 263)
Settings_2.Visible = false

DarkMode.Name = "DarkMode"
DarkMode.Parent = Settings_2
DarkMode.BackgroundColor3 = Color3.new(0.168627, 0.172549, 0.168627)
DarkMode.BorderSizePixel = 0
DarkMode.ClipsDescendants = true
DarkMode.Position = UDim2.new(0.877889037, -100, 0.233662367, -25)
DarkMode.Size = UDim2.new(0, 169, 0, 50)
DarkMode.AutoButtonColor = false
DarkMode.Font = Enum.Font.SourceSansLight
DarkMode.Text = "Dark Mode"
DarkMode.TextColor3 = Color3.new(1, 1, 1)
DarkMode.TextSize = 18

toggle.Name = "toggle"
toggle.Parent = Settings_2
toggle.BackgroundColor3 = Color3.new(1, 1, 1)
toggle.BackgroundTransparency = 1
toggle.Position = UDim2.new(0.706821501, 0, 0.817490458, 0)
toggle.Size = UDim2.new(0, 200, 0, 50)
toggle.Font = Enum.Font.SourceSansLight
toggle.Text = "Press 'p' on your keyboard to toggle the gui!"
toggle.TextColor3 = Color3.new(0, 0, 0)
toggle.TextScaled = true
toggle.TextSize = 14
toggle.TextWrapped = true

Size.Name = "Size"
Size.Parent = Settings_2
Size.BackgroundColor3 = Color3.new(0.819608, 0.819608, 0.819608)
Size.BorderSizePixel = 0
Size.Position = UDim2.new(0.35558781, 0, 0.328719348, 0)
Size.Size = UDim2.new(0, 200, 0, 38)
Size.ClearTextOnFocus = false
Size.Font = Enum.Font.Code
Size.Text = "0, 690,0, 363"
Size.TextColor3 = Color3.new(0, 0, 0)
Size.TextScaled = true
Size.TextSize = 14
Size.TextWrapped = true

Change.Name = "Change"
Change.Parent = Size
Change.BackgroundColor3 = Color3.new(0.298039, 0.407843, 0.709804)
Change.BorderSizePixel = 0
Change.ClipsDescendants = true
Change.Position = UDim2.new(0.583752573, -100, 1.96450078, -25)
Change.Size = UDim2.new(0, 169, 0, 50)
Change.AutoButtonColor = false
Change.Font = Enum.Font.SourceSansLight
Change.Text = "Change"
Change.TextColor3 = Color3.new(1, 1, 1)
Change.TextSize = 18

TextLabel.Parent = Size
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0, 0, -1.60526311, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.SourceSansLight
TextLabel.Text = "GUI Size:"
TextLabel.TextColor3 = Color3.new(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true

RainbowTopBar.Name = "RainbowTopBar"
RainbowTopBar.Parent = Settings_2
RainbowTopBar.BackgroundColor3 = Color3.new(1, 0.117647, 0.117647)
RainbowTopBar.BorderSizePixel = 0
RainbowTopBar.ClipsDescendants = true
RainbowTopBar.Position = UDim2.new(0.184129953, -100, 0.233662367, -25)
RainbowTopBar.Size = UDim2.new(0, 169, 0, 50)
RainbowTopBar.AutoButtonColor = false
RainbowTopBar.Font = Enum.Font.SourceSansLight
RainbowTopBar.Text = "Rainbow Topbar"
RainbowTopBar.TextColor3 = Color3.new(1, 1, 1)
RainbowTopBar.TextSize = 18

DFeatures.Name = "DFeatures"
DFeatures.Parent = Settings_2
DFeatures.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
DFeatures.Position = UDim2.new(0.0275761969, 0, 0.863117874, 0)
DFeatures.Size = UDim2.new(0, 411, 0, 26)
DFeatures.SizeConstraint = Enum.SizeConstraint.RelativeYY
DFeatures.ClearTextOnFocus = false
DFeatures.Font = Enum.Font.Code
DFeatures.Text = "Add special features here."
DFeatures.TextColor3 = Color3.new(1, 1, 1)
DFeatures.TextSize = 21
DFeatures.TextWrapped = true
DFeatures.TextXAlignment = Enum.TextXAlignment.Left

Load.Name = "Load"
Load.Parent = DFeatures
Load.BackgroundColor3 = Color3.new(0.439216, 0.839216, 0.47451)
Load.BorderSizePixel = 0
Load.Position = UDim2.new(1.03649628, 0, -0.230769232, 0)
Load.Size = UDim2.new(0, 42, 0, 38)
Load.Font = Enum.Font.SourceSans
Load.Text = "Load"
Load.TextColor3 = Color3.new(0, 0, 0)
Load.TextSize = 14

LocalPlayer_2.Name = "LocalPlayer"
LocalPlayer_2.Parent = MainGUI
LocalPlayer_2.BackgroundColor3 = Color3.new(1, 1, 1)
LocalPlayer_2.BorderSizePixel = 0
LocalPlayer_2.Position = UDim2.new(0, 0, 0.272727281, 0)
LocalPlayer_2.Size = UDim2.new(0, 691, 0, 264)
LocalPlayer_2.Visible = false

Fire.Name = "Fire"
Fire.Parent = LocalPlayer_2
Fire.BackgroundColor3 = Color3.new(1, 0.113725, 0.113725)
Fire.BorderSizePixel = 0
Fire.Position = UDim2.new(0.0680173635, 0, 0.064393945, 0)
Fire.Size = UDim2.new(0, 141, 0, 55)
Fire.Font = Enum.Font.SourceSansLight
Fire.Text = "Fire"
Fire.TextColor3 = Color3.new(0, 0, 0)
Fire.TextScaled = true
Fire.TextSize = 14
Fire.TextWrapped = true

Sparkes.Name = "Sparkes"
Sparkes.Parent = LocalPlayer_2
Sparkes.BackgroundColor3 = Color3.new(1, 0.341176, 0.992157)
Sparkes.BorderSizePixel = 0
Sparkes.Position = UDim2.new(0.0680173635, 0, 0.689393938, 0)
Sparkes.Size = UDim2.new(0, 141, 0, 55)
Sparkes.Font = Enum.Font.SourceSansLight
Sparkes.Text = "Sparkles"
Sparkes.TextColor3 = Color3.new(0, 0, 0)
Sparkes.TextScaled = true
Sparkes.TextSize = 14
Sparkes.TextWrapped = true

Fly.Name = "Fly"
Fly.Parent = LocalPlayer_2
Fly.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.396526784, 0, 0.0643939599, 0)
Fly.Size = UDim2.new(0, 141, 0, 55)
Fly.Font = Enum.Font.SourceSansLight
Fly.Text = "Fly"
Fly.TextColor3 = Color3.new(0, 0, 0)
Fly.TextScaled = true
Fly.TextSize = 14
Fly.TextWrapped = true

Walkspeed.Name = "Walkspeed"
Walkspeed.Parent = LocalPlayer_2
Walkspeed.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
Walkspeed.BorderSizePixel = 0
Walkspeed.Position = UDim2.new(0.397973955, 0, 0.689393938, 0)
Walkspeed.Size = UDim2.new(0, 141, 0, 55)
Walkspeed.Font = Enum.Font.SourceSansLight
Walkspeed.Text = "WalkSpeed"
Walkspeed.TextColor3 = Color3.new(0, 0, 0)
Walkspeed.TextScaled = true
Walkspeed.TextSize = 14
Walkspeed.TextWrapped = true

JumpPower.Name = "JumpPower"
JumpPower.Parent = LocalPlayer_2
JumpPower.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
JumpPower.BorderSizePixel = 0
JumpPower.Position = UDim2.new(0.752532542, 0, 0.689393938, 0)
JumpPower.Size = UDim2.new(0, 141, 0, 55)
JumpPower.Font = Enum.Font.SourceSansLight
JumpPower.Text = "JumpPower"
JumpPower.TextColor3 = Color3.new(0, 0, 0)
JumpPower.TextScaled = true
JumpPower.TextSize = 14
JumpPower.TextWrapped = true

Gravity.Name = "Gravity"
Gravity.Parent = LocalPlayer_2
Gravity.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
Gravity.BorderSizePixel = 0
Gravity.Position = UDim2.new(0.753979743, 0, 0.0643939599, 0)
Gravity.Size = UDim2.new(0, 141, 0, 55)
Gravity.Font = Enum.Font.SourceSansLight
Gravity.Text = "Gravity"
Gravity.TextColor3 = Color3.new(0, 0, 0)
Gravity.TextScaled = true
Gravity.TextSize = 14
Gravity.TextWrapped = true

Noclip.Name = "Noclip"
Noclip.Parent = LocalPlayer_2
Noclip.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
Noclip.BorderSizePixel = 0
Noclip.Position = UDim2.new(0.0680173635, 0, 0.371212155, 0)
Noclip.Size = UDim2.new(0, 141, 0, 55)
Noclip.Font = Enum.Font.SourceSansLight
Noclip.Text = "Noclip"
Noclip.TextColor3 = Color3.new(0, 0, 0)
Noclip.TextScaled = true
Noclip.TextSize = 14
Noclip.TextWrapped = true

FEInvisible.Name = "FE Invisible"
FEInvisible.Parent = LocalPlayer_2
FEInvisible.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
FEInvisible.BorderSizePixel = 0
FEInvisible.Position = UDim2.new(0.397973925, 0, 0.371212155, 0)
FEInvisible.Size = UDim2.new(0, 141, 0, 55)
FEInvisible.Font = Enum.Font.SourceSansLight
FEInvisible.Text = "FE Invisible"
FEInvisible.TextColor3 = Color3.new(0, 0, 0)
FEInvisible.TextScaled = true
FEInvisible.TextSize = 14
FEInvisible.TextWrapped = true

god.Name = "god"
god.Parent = LocalPlayer_2
god.BackgroundColor3 = Color3.new(0.839216, 0.839216, 0.819608)
god.BorderSizePixel = 0
god.Position = UDim2.new(0.752532542, 0, 0.371212155, 0)
god.Size = UDim2.new(0, 141, 0, 55)
god.Font = Enum.Font.SourceSansLight
god.Text = "FE God (Lose some abilities)"
god.TextColor3 = Color3.new(0, 0, 0)
god.TextScaled = true
god.TextSize = 14
god.TextWrapped = true

LoginGUI.Name = "LoginGUI"
LoginGUI.Parent = AdminMenuViown
LoginGUI.Active = true
LoginGUI.BackgroundColor3 = Color3.new(1, 1, 1)
LoginGUI.BackgroundTransparency = 1
LoginGUI.Position = UDim2.new(0.350848854, 0, 0.10702341, 0)
LoginGUI.Selectable = true
LoginGUI.Size = UDim2.new(0, 462, 0, 392)
LoginGUI.Image = "rbxassetid://2803731757"
LoginGUI.ImageColor3 = Color3.new(0.156863, 0.156863, 0.156863)
LoginGUI.ScaleType = Enum.ScaleType.Slice
LoginGUI.SliceCenter = Rect.new(14, 14, 15, 15)

Login.Name = "Login"
Login.Parent = LoginGUI
Login.BackgroundColor3 = Color3.new(0.960784, 0.960784, 0.960784)
Login.BorderColor3 = Color3.new(0.560784, 0.584314, 0.47451)
Login.BorderSizePixel = 2
Login.Position = UDim2.new(0.194805205, 0, 0.328840971, 0)
Login.Size = UDim2.new(0, 282, 0, 32)
Login.ClearTextOnFocus = false
Login.Font = Enum.Font.SourceSansBold
Login.Text = ""
Login.TextColor3 = Color3.new(0.654902, 0.654902, 0.654902)
Login.TextScaled = true
Login.TextSize = 14
Login.TextTransparency = 0.5
Login.TextWrapped = true
Login.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_2.Parent = Login
TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_2.BackgroundTransparency = 1
TextLabel_2.Position = UDim2.new(-0.0390070938, 0, -0.90625, 0)
TextLabel_2.Size = UDim2.new(0, 128, 0, 29)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Username:"
TextLabel_2.TextColor3 = Color3.new(0.901961, 0.901961, 0.901961)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14
TextLabel_2.TextTransparency = 0.5
TextLabel_2.TextWrapped = true

Password.Name = "Password"
Password.Parent = LoginGUI
Password.BackgroundColor3 = Color3.new(0.952941, 0.952941, 0.952941)
Password.BorderColor3 = Color3.new(0.843137, 0.901961, 0.866667)
Password.BorderSizePixel = 2
Password.Position = UDim2.new(0.194805205, 0, 0.520215631, 0)
Password.Size = UDim2.new(0, 282, 0, 32)
Password.ClearTextOnFocus = false
Password.Font = Enum.Font.SourceSansBold
Password.Text = ""
Password.TextColor3 = Color3.new(0.690196, 0.690196, 0.690196)
Password.TextScaled = true
Password.TextSize = 14
Password.TextTransparency = 0.5
Password.TextWrapped = true
Password.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_3.Parent = Password
TextLabel_3.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_3.BackgroundTransparency = 1
TextLabel_3.Position = UDim2.new(-0.0390070938, 0, -0.90625, 0)
TextLabel_3.Size = UDim2.new(0, 128, 0, 29)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Password:"
TextLabel_3.TextColor3 = Color3.new(0.901961, 0.901961, 0.901961)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14
TextLabel_3.TextTransparency = 0.5
TextLabel_3.TextWrapped = true

Frame.Parent = LoginGUI
Frame.BackgroundColor3 = Color3.new(0.6, 0.6, 0.6)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.255411267, 0, 0.762803257, 0)
Frame.Size = UDim2.new(0, 226, 0, 65)

Access.Name = "Access"
Access.Parent = Frame
Access.BackgroundColor3 = Color3.new(0.776471, 0.776471, 0.776471)
Access.BorderSizePixel = 0
Access.Position = UDim2.new(-0.0619469024, 0, -0.169230729, 0)
Access.Size = UDim2.new(0, 226, 0, 65)
Access.Font = Enum.Font.SourceSansLight
Access.Text = "Access"
Access.TextColor3 = Color3.new(0, 0, 0)
Access.TextScaled = true
Access.TextSize = 14
Access.TextWrapped = true

ForgotPassword.Name = "Forgot Password"
ForgotPassword.Parent = Frame
ForgotPassword.BackgroundColor3 = Color3.new(0.74902, 0.792157, 0.741176)
ForgotPassword.BackgroundTransparency = 1
ForgotPassword.BorderSizePixel = 0
ForgotPassword.Position = UDim2.new(-0.492701977, 0, 0.101923078, 0)
ForgotPassword.Size = UDim2.new(0, 90, 0, 58)
ForgotPassword.Font = Enum.Font.SourceSansBold
ForgotPassword.Text = "Forgot Password?"
ForgotPassword.TextColor3 = Color3.new(0.8, 0.8, 0.74902)
ForgotPassword.TextScaled = true
ForgotPassword.TextSize = 14
ForgotPassword.TextStrokeTransparency = 0.80000001192093
ForgotPassword.TextWrapped = true

Info.Name = "Info"
Info.Parent = ForgotPassword
Info.Active = true
Info.BackgroundColor3 = Color3.new(1, 1, 1)
Info.BackgroundTransparency = 1
Info.Position = UDim2.new(-1.01111102, 0, -3.74137878, 0)
Info.Selectable = true
Info.Size = UDim2.new(0, 602, 0, 332)
Info.Visible = false
Info.Image = "rbxassetid://2803732984"
Info.ImageColor3 = Color3.new(0.117647, 0.117647, 0.117647)
Info.ScaleType = Enum.ScaleType.Slice
Info.SliceCenter = Rect.new(15, 15, 16, 16)

TextLabel_4.Parent = Info
TextLabel_4.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_4.BackgroundTransparency = 1
TextLabel_4.Position = UDim2.new(0, 0, 0.0903614461, 0)
TextLabel_4.Size = UDim2.new(0, 602, 0, 302)
TextLabel_4.Font = Enum.Font.SourceSansSemibold
TextLabel_4.Text = "If you forgot your password and you don't have it saved, don't worry! There are two ways to get it.  A: Go to vi#9292's dms, and find your account and password. They should be there. B: If it isn't there talk to vi#9292 and you will  be guided to get it back."
TextLabel_4.TextColor3 = Color3.new(1, 1, 1)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14
TextLabel_4.TextStrokeTransparency = 0
TextLabel_4.TextWrapped = true

TextButton.Parent = Info
TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton.BackgroundTransparency = 1
TextButton.Position = UDim2.new(0.926910281, 0, 0, 0)
TextButton.Size = UDim2.new(0, 55, 0, 50)
TextButton.Font = Enum.Font.SourceSansSemibold
TextButton.Text = "X"
TextButton.TextColor3 = Color3.new(1, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14
TextButton.TextWrapped = true

Top_3.Name = "Top"
Top_3.Parent = LoginGUI
Top_3.BackgroundColor3 = Color3.new(1, 1, 1)
Top_3.BackgroundTransparency = 1
Top_3.Size = UDim2.new(0, 462, 0, 61)
Top_3.Image = "rbxassetid://2803731757"
Top_3.ImageColor3 = Color3.new(0.0470588, 0.105882, 0.0901961)
Top_3.ScaleType = Enum.ScaleType.Slice
Top_3.SliceCenter = Rect.new(14, 14, 15, 15)

TopText_2.Name = "TopText"
TopText_2.Parent = Top_3
TopText_2.BackgroundColor3 = Color3.new(1, 1, 1)
TopText_2.BackgroundTransparency = 1
TopText_2.Size = UDim2.new(0, 462, 0, 61)
TopText_2.Font = Enum.Font.SourceSansLight
TopText_2.Text = "Admin Menu Login"
TopText_2.TextColor3 = Color3.new(1, 1, 1)
TopText_2.TextScaled = true
TopText_2.TextSize = 14
TopText_2.TextStrokeTransparency = 0.89999997615814
TopText_2.TextWrapped = true

Spin.Name = "Spin"
Spin.Parent = LoginGUI
Spin.BackgroundColor3 = Color3.new(1, 1, 1)
Spin.BackgroundTransparency = 1
Spin.Position = UDim2.new(0.333333343, 0, 0.237244904, 0)
Spin.Size = UDim2.new(0, 136, 0, 136)
Spin.Visible = false
Spin.Image = "rbxassetid://2804206750"
Spin.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
Spin.ScaleType = Enum.ScaleType.Slice
Spin.SliceCenter = Rect.new(12, 12, 13, 13)

TextHit.Name = "TextHit"
TextHit.Parent = LoginGUI
TextHit.BackgroundColor3 = Color3.new(1, 1, 1)
TextHit.BackgroundTransparency = 1
TextHit.Position = UDim2.new(0, 0, 0.714285731, 0)
TextHit.Size = UDim2.new(0, 462, 0, 50)
TextHit.Visible = false
TextHit.Font = Enum.Font.GothamBlack
TextHit.Text = "-V-"
TextHit.TextColor3 = Color3.new(1, 1, 1)
TextHit.TextScaled = true
TextHit.TextSize = 14
TextHit.TextWrapped = true
-- Scripts:
function SCRIPT_ACCF81_FAKESCRIPT() -- General.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = General
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.General.Visible = true;
	script.Parent.Parent.Parent.Settings.Visible = false;
	script.Parent.Parent.Parent.Credits.Visible = false;
	script.Parent.Parent.Parent.Scripts.Visible = false;
	script.Parent.Parent.Parent.LocalPlayer.Visible = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_ACCF81_FAKESCRIPT))
function SCRIPT_RWSM76_FAKESCRIPT() -- General.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = General
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_RWSM76_FAKESCRIPT))
function SCRIPT_YENB87_FAKESCRIPT() -- TopText.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = TopText
	while true do
	Light = script.Parent
	Old = Light.BackgroundColor3
	New = Color3.new(math.random(0,255)/255,math.random(0,255)/255,math.random(0,255)/255)
	
	R = false
	G = false
	B = false
	
	coroutine.resume(coroutine.create(function()
		if New.r > Old.r then
			for i = Old.r, New.r, 2/255 do
				Light.BackgroundColor3 =  Color3.new(i,Light.BackgroundColor3.g,Light.BackgroundColor3.b)
				wait()
			end
		elseif New.r < Old.r then
			for i = Old.r, New.r, -2/255 do
				Light.BackgroundColor3 =  Color3.new(i,Light.BackgroundColor3.g,Light.BackgroundColor3.b)
				wait()
			end
		end
		R = true
	end))
	
	coroutine.resume(coroutine.create(function()
		if New.g > Old.g then
			for i = Old.g,New.g,2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,i,Light.BackgroundColor3.b)
				wait()
			end
		else
			for i = Old.g,New.g,-2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,i,Light.BackgroundColor3.b)
				wait()
			end
		end
		G = true
	end))
	
	coroutine.resume(coroutine.create(function()
		if New.b > Old.b then
			for i = Old.b,New.b,2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,Light.BackgroundColor3.g,i)
				wait()
			end
		else
			for i = Old.b,New.b,-2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,Light.BackgroundColor3.g,i)
				wait()
			end
		end
		B = true
	end))
	
	repeat wait(1/30) until R == true and G == true and B == true
	
	end

end
coroutine.resume(coroutine.create(SCRIPT_YENB87_FAKESCRIPT))
function SCRIPT_NAVS77_FAKESCRIPT() -- Version.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Version
	script.Parent.Text = script.Parent.Parent.Parent.Parent.Parent.Version.Value

end
coroutine.resume(coroutine.create(SCRIPT_NAVS77_FAKESCRIPT))
function SCRIPT_PRWJ69_FAKESCRIPT() -- LocalPlayer.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = LocalPlayer
	local btn=script.Parent
	
	btn.MouseButton1Down:Connect(function()
	script.Parent.Parent.Parent.General.Visible = false;
	script.Parent.Parent.Parent.Settings.Visible = false;
	script.Parent.Parent.Parent.Scripts.Visible = false;
	script.Parent.Parent.Parent.Credits.Visible = false;
	script.Parent.Parent.Parent.LocalPlayer.Visible = true;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_PRWJ69_FAKESCRIPT))
function SCRIPT_EGVK67_FAKESCRIPT() -- LocalPlayer.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = LocalPlayer
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_EGVK67_FAKESCRIPT))
function SCRIPT_JOSW72_FAKESCRIPT() -- Scripts.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Scripts
	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.General.Visible = false;
	script.Parent.Parent.Parent.Settings.Visible = false;
	script.Parent.Parent.Parent.Scripts.Visible = true;
	script.Parent.Parent.Parent.Credits.Visible = false;
	script.Parent.Parent.Parent.LocalPlayer.Visible = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_JOSW72_FAKESCRIPT))
function SCRIPT_YNEB86_FAKESCRIPT() -- Scripts.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Scripts
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_YNEB86_FAKESCRIPT))
function SCRIPT_LQPX65_FAKESCRIPT() -- Settings.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Settings
	local btn=script.Parent
	
	btn.MouseButton1Down:Connect(function()
	script.Parent.Parent.Parent.General.Visible = false;
	script.Parent.Parent.Parent.Settings.Visible = true;
	script.Parent.Parent.Parent.Credits.Visible = false;
	script.Parent.Parent.Parent.Scripts.Visible = false;
	script.Parent.Parent.Parent.LocalPlayer.Visible = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_LQPX65_FAKESCRIPT))
function SCRIPT_AAJD79_FAKESCRIPT() -- Settings.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Settings
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_AAJD79_FAKESCRIPT))
function SCRIPT_TUGY76_FAKESCRIPT() -- X.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = X
	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.Visible = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_TUGY76_FAKESCRIPT))
function SCRIPT_EOQM73_FAKESCRIPT() -- MainGUI.Drag 
	local script = Instance.new('LocalScript')
	script.Parent = MainGUI
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
coroutine.resume(coroutine.create(SCRIPT_EOQM73_FAKESCRIPT))
function SCRIPT_DLEP65_FAKESCRIPT() -- Execute.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Execute
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(script.Parent.Parent.Code.Text)
	end)

end
coroutine.resume(coroutine.create(SCRIPT_DLEP65_FAKESCRIPT))
function SCRIPT_BCRA78_FAKESCRIPT() -- Execute.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Execute
	local Mouse = game.Players.LocalPlayer:GetMouse()
	
	local function CircleClick(Button, X, Y)
			
			Button.ClipsDescendants = true
			
			local Circle = script:WaitForChild("Circle"):Clone()
				Circle.Parent = Button
				local NewX = X - Circle.AbsolutePosition.X
				local NewY = Y - Circle.AbsolutePosition.Y
				Circle.Position = UDim2.new(0, NewX, 0, NewY)
			
			local Size = 0
				if Button.AbsoluteSize.X > Button.AbsoluteSize.Y then
					 Size = Button.AbsoluteSize.X*1.5
				elseif Button.AbsoluteSize.X < Button.AbsoluteSize.Y then
					 Size = Button.AbsoluteSize.Y*1.5
				elseif Button.AbsoluteSize.X == Button.AbsoluteSize.Y then																																																																														print("This place uses a model by Come0n.") --please do not remove!
					Size = Button.AbsoluteSize.X*1.5
				end
			
			local Time = 0.5
				Circle:TweenSizeAndPosition(UDim2.new(0, Size, 0, Size), UDim2.new(0.5, -Size/2, 0.5, -Size/2), "Out", "Quad", Time, false, nil)
				for i=1,10 do
					Circle.ImageTransparency = Circle.ImageTransparency + 0.01
					wait(Time/10)
				end
				Circle:Destroy()
	end
	
	
	script.Parent.MouseButton1Down:connect(function()
		CircleClick(script.Parent, Mouse.X, Mouse.Y) 
	end)
	
	
	

end
coroutine.resume(coroutine.create(SCRIPT_BCRA78_FAKESCRIPT))
function SCRIPT_XMNX84_FAKESCRIPT() -- Clear.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Clear
	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Parent.Code.Text = "";
	end)

end
coroutine.resume(coroutine.create(SCRIPT_XMNX84_FAKESCRIPT))
function SCRIPT_FKEO65_FAKESCRIPT() -- Clear.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Clear
	local Mouse = game.Players.LocalPlayer:GetMouse()
	
	local function CircleClick(Button, X, Y)
			
			Button.ClipsDescendants = true
			
			local Circle = script:WaitForChild("Circle"):Clone()
				Circle.Parent = Button
				local NewX = X - Circle.AbsolutePosition.X
				local NewY = Y - Circle.AbsolutePosition.Y
				Circle.Position = UDim2.new(0, NewX, 0, NewY)
			
			local Size = 0
				if Button.AbsoluteSize.X > Button.AbsoluteSize.Y then
					 Size = Button.AbsoluteSize.X*1.5
				elseif Button.AbsoluteSize.X < Button.AbsoluteSize.Y then
					 Size = Button.AbsoluteSize.Y*1.5
				elseif Button.AbsoluteSize.X == Button.AbsoluteSize.Y then																																																																														print("This place uses a model by Come0n.") --please do not remove!
					Size = Button.AbsoluteSize.X*1.5
				end
			
			local Time = 0.5
				Circle:TweenSizeAndPosition(UDim2.new(0, Size, 0, Size), UDim2.new(0.5, -Size/2, 0.5, -Size/2), "Out", "Quad", Time, false, nil)
				for i=1,10 do
					Circle.ImageTransparency = Circle.ImageTransparency + 0.01
					wait(Time/10)
				end
				Circle:Destroy()
	end
	
	
	script.Parent.MouseButton1Down:connect(function()
		CircleClick(script.Parent, Mouse.X, Mouse.Y) 
	end)
	
	
	

end
coroutine.resume(coroutine.create(SCRIPT_FKEO65_FAKESCRIPT))
function SCRIPT_BGBQ86_FAKESCRIPT() -- Close.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Close
	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Parent.Visible = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_BGBQ86_FAKESCRIPT))
function SCRIPT_RHST85_FAKESCRIPT() -- Close.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Close
	local Mouse = game.Players.LocalPlayer:GetMouse()
	
	local function CircleClick(Button, X, Y)
			
			Button.ClipsDescendants = true
			
			local Circle = script:WaitForChild("Circle"):Clone()
				Circle.Parent = Button
				local NewX = X - Circle.AbsolutePosition.X
				local NewY = Y - Circle.AbsolutePosition.Y
				Circle.Position = UDim2.new(0, NewX, 0, NewY)
			
			local Size = 0
				if Button.AbsoluteSize.X > Button.AbsoluteSize.Y then
					 Size = Button.AbsoluteSize.X*1.5
				elseif Button.AbsoluteSize.X < Button.AbsoluteSize.Y then
					 Size = Button.AbsoluteSize.Y*1.5
				elseif Button.AbsoluteSize.X == Button.AbsoluteSize.Y then																																																																														print("This place uses a model by Come0n.") --please do not remove!
					Size = Button.AbsoluteSize.X*1.5
				end
			
			local Time = 0.5
				Circle:TweenSizeAndPosition(UDim2.new(0, Size, 0, Size), UDim2.new(0.5, -Size/2, 0.5, -Size/2), "Out", "Quad", Time, false, nil)
				for i=1,10 do
					Circle.ImageTransparency = Circle.ImageTransparency + 0.01
					wait(Time/10)
				end
				Circle:Destroy()
	end
	
	
	script.Parent.MouseButton1Down:connect(function()
		CircleClick(script.Parent, Mouse.X, Mouse.Y) 
	end)
	
	
	

end
coroutine.resume(coroutine.create(SCRIPT_RHST85_FAKESCRIPT))
function SCRIPT_MIFU75_FAKESCRIPT() -- Executor.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Executor
	script.Parent.Draggable = true;

end
coroutine.resume(coroutine.create(SCRIPT_MIFU75_FAKESCRIPT))
function SCRIPT_TKFD86_FAKESCRIPT() -- Shattervast.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Shattervast
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/gtrWL0s2'),true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_TKFD86_FAKESCRIPT))
function SCRIPT_MFXL73_FAKESCRIPT() -- Shattervast.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Shattervast
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_MFXL73_FAKESCRIPT))
function SCRIPT_EOVP88_FAKESCRIPT() -- ExecutorLoader.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = ExecutorLoader
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.Executor.Visible = true;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_EOVP88_FAKESCRIPT))
function SCRIPT_GSAS82_FAKESCRIPT() -- ExecutorLoader.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = ExecutorLoader
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_GSAS82_FAKESCRIPT))
function SCRIPT_CNID85_FAKESCRIPT() -- InfiniteYield.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = InfiniteYield
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/MjBzRjmT'),true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_CNID85_FAKESCRIPT))
function SCRIPT_TACX85_FAKESCRIPT() -- InfiniteYield.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = InfiniteYield
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_TACX85_FAKESCRIPT))
function SCRIPT_WIRF73_FAKESCRIPT() -- N3xulis.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = N3xulis
	local btn=script.Parent
	
	btn.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/X16dnsUb'), true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_WIRF73_FAKESCRIPT))
function SCRIPT_TSSJ77_FAKESCRIPT() -- N3xulis.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = N3xulis
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_TSSJ77_FAKESCRIPT))
function SCRIPT_MAMG79_FAKESCRIPT() -- TrollGUI.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = TrollGUI
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/nwGzXh1V",true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_MAMG79_FAKESCRIPT))
function SCRIPT_FYPF76_FAKESCRIPT() -- TrollGUI.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = TrollGUI
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_FYPF76_FAKESCRIPT))
function SCRIPT_TTTI77_FAKESCRIPT() -- MusicPlayer.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = MusicPlayer
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/kq0MAcin",true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_TTTI77_FAKESCRIPT))
function SCRIPT_RHVK83_FAKESCRIPT() -- MusicPlayer.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = MusicPlayer
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_RHVK83_FAKESCRIPT))
function SCRIPT_DADG89_FAKESCRIPT() -- FEFlingKill.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = FEFlingKill
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	local FlingKill = Instance.new("ScreenGui")
	local Main = Instance.new("Frame")
	local Label = Instance.new("Frame")
	local Shadow = Instance.new("Frame")
	local StartKill = Instance.new("TextButton")
	local StopKill = Instance.new("TextButton")
	local Instructions = Instance.new("TextLabel")
	local CurrentPower = Instance.new("TextLabel")
	local Recomendation = Instance.new("TextLabel")
	local NameOfGui = Instance.new("TextLabel")
	local Exit = Instance.new("TextButton")
	local UPArrow = Instance.new("TextButton")
	local DownArrow = Instance.new("TextButton")
	
	-- Properties
	
	FlingKill.Name = "Fling/Kill"
	FlingKill.Parent = game.CoreGui
	
	Main.Name = "Main"
	Main.Parent = FlingKill
	Main.BackgroundColor3 = Color3.new(0.92549, 0.941177, 0.945098)
	Main.BorderSizePixel = 0
	Main.Position = UDim2.new(0.702554762, 0, 0.446640313, 0)
	Main.Size = UDim2.new(0, 217, 0, 233)
	Main.Selectable = true
	Main.Active = true
	Main.Draggable = true
	
	Label.Name = "Label"
	Label.Parent = Main
	Label.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)
	Label.BorderSizePixel = 0
	Label.Size = UDim2.new(0, 217, 0, 27)
	
	Shadow.Name = "Shadow"
	Shadow.Parent = Main
	Shadow.BackgroundColor3 = Color3.new(0.67451, 0.694118, 0.705882)
	Shadow.BorderSizePixel = 0
	Shadow.Position = UDim2.new(0, 0, 0.115879826, 0)
	Shadow.Size = UDim2.new(0, 217, 0, 9)
	
	StartKill.Name = "StartKill"
	StartKill.Parent = Main
	StartKill.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)
	StartKill.BorderSizePixel = 0
	StartKill.Position = UDim2.new(0.195852548, 0, 0.227467805, 0)
	StartKill.Size = UDim2.new(0, 126, 0, 23)
	StartKill.Font = Enum.Font.Cartoon
	StartKill.Text = "FE Kill/Fling"
	StartKill.TextColor3 = Color3.new(0, 0, 0)
	StartKill.TextSize = 14
	
	StopKill.Name = "StopKill"
	StopKill.Parent = Main
	StopKill.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)
	StopKill.BorderSizePixel = 0
	StopKill.Position = UDim2.new(0.207373276, 0, 0.38197428, 0)
	StopKill.Size = UDim2.new(0, 124, 0, 23)
	StopKill.Font = Enum.Font.Cartoon
	StopKill.Text = "Stop FE Kill/Fling"
	StopKill.TextColor3 = Color3.new(0, 0, 0)
	StopKill.TextSize = 14
	
	Instructions.Name = "Instructions"
	Instructions.Parent = Main
	Instructions.BackgroundColor3 = Color3.new(1, 1, 1)
	Instructions.BackgroundTransparency = 1
	Instructions.Position = UDim2.new(0.0391705073, 0, 0.549356222, 0)
	Instructions.Size = UDim2.new(0, 200, 0, 32)
	Instructions.Font = Enum.Font.Cartoon
	Instructions.Text = "Just touch someone to watch the fly to their death!"
	Instructions.TextColor3 = Color3.new(0, 0, 0)
	Instructions.TextSize = 14
	Instructions.TextWrapped = true
	
	CurrentPower.Name = "CurrentPower"
	CurrentPower.Parent = Main
	CurrentPower.BackgroundColor3 = Color3.new(1, 1, 1)
	CurrentPower.BackgroundTransparency = 1
	CurrentPower.Position = UDim2.new(0.276497692, 0, 0.686695278, 0)
	CurrentPower.Size = UDim2.new(0, 98, 0, 36)
	CurrentPower.Font = Enum.Font.Cartoon
	CurrentPower.Text = "Current Power = 5"
	CurrentPower.TextColor3 = Color3.new(0, 0, 0)
	CurrentPower.TextSize = 14
	
	Recomendation.Name = "Recomendation"
	Recomendation.Parent = Main
	Recomendation.BackgroundColor3 = Color3.new(1, 1, 1)
	Recomendation.BackgroundTransparency = 1
	Recomendation.Position = UDim2.new(0.0414746553, 0, 0.884120166, 0)
	Recomendation.Size = UDim2.new(0, 200, 0, 21)
	Recomendation.Font = Enum.Font.Cartoon
	Recomendation.Text = "Recommended Power is 5"
	Recomendation.TextColor3 = Color3.new(0, 0, 0)
	Recomendation.TextSize = 14
	
	NameOfGui.Name = "NameOfGui"
	NameOfGui.Parent = Main
	NameOfGui.BackgroundColor3 = Color3.new(1, 1, 1)
	NameOfGui.BackgroundTransparency = 1
	NameOfGui.Position = UDim2.new(0.0806451589, 0, 0, 0)
	NameOfGui.Size = UDim2.new(0, 154, 0, 27)
	NameOfGui.Font = Enum.Font.Cartoon
	NameOfGui.Text = "FE Kill/Fling By JackMcJagger15"
	NameOfGui.TextColor3 = Color3.new(0, 0, 0)
	NameOfGui.TextSize = 14
	
	Exit.Name = "Exit"
	Exit.Parent = Main
	Exit.BackgroundColor3 = Color3.new(1, 1, 1)
	Exit.BackgroundTransparency = 1
	Exit.Position = UDim2.new(0.907834113, 0, 0, 0)
	Exit.Size = UDim2.new(0, 20, 0, 27)
	Exit.Font = Enum.Font.Cartoon
	Exit.Text = "X"
	Exit.TextColor3 = Color3.new(0, 0, 0)
	Exit.TextSize = 14
	
	UPArrow.Name = "UPArrow"
	UPArrow.Parent = Main
	UPArrow.BackgroundColor3 = Color3.new(1, 1, 1)
	UPArrow.BackgroundTransparency = 1
	UPArrow.Position = UDim2.new(0.0783410147, 0, 0.716738224, 0)
	UPArrow.Size = UDim2.new(0, 26, 0, 23)
	UPArrow.Font = Enum.Font.Cartoon
	UPArrow.Text = "Up"
	UPArrow.TextColor3 = Color3.new(0, 0, 0)
	UPArrow.TextSize = 12
	UPArrow.TextWrapped = true
	
	DownArrow.Name = "DownArrow"
	DownArrow.Parent = Main
	DownArrow.BackgroundColor3 = Color3.new(1, 1, 1)
	DownArrow.BackgroundTransparency = 1
	DownArrow.Position = UDim2.new(0.792626739, 0, 0.714592278, 0)
	DownArrow.Size = UDim2.new(0, 26, 0, 23)
	DownArrow.Font = Enum.Font.Cartoon
	DownArrow.Text = "Down"
	DownArrow.TextColor3 = Color3.new(0, 0, 0)
	DownArrow.TextSize = 12
	DownArrow.TextWrapped = true
	
	power = 500
	active = false
	local val = Instance.new("IntValue")
	val.Name = "Number"
	val.Parent = game.Players.LocalPlayer
	val.Value = 5
	
	Exit.MouseButton1Click:connect(function()
	FlingKill.Enabled = false
	end)
	
	StartKill.MouseButton1Click:connect(function()
	game:GetService('RunService').Stepped:connect(function()
	if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then
	game.Players.LocalPlayer.Character.Head.CanCollide = false
	game.Players.LocalPlayer.Character.Torso.CanCollide = false
	game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
	game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
	else
	if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then
	game.Players.LocalPlayer.Character.Head.CanCollide = false
	game.Players.LocalPlayer.Character.UpperTorso.CanCollide = false
	game.Players.LocalPlayer.Character.LowerTorso.CanCollide = false
	game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false
	end
	end
	end)
	wait(.1)
	local bambam = Instance.new("BodyThrust")
	bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
	bambam.Force = Vector3.new(power,0,power)
	bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
	end)
	
	StopKill.MouseButton1Click:connect(function()
	active = false
	game.Players.LocalPlayer.Character.HumanoidRootPart.BodyThrust:Remove()
	end)
	
	UPArrow.MouseButton1Click:connect(function()
	power = power + 100
	game.Players.LocalPlayer.Number.Value = game.Players.LocalPlayer.Number.Value + 1
	CurrentPower.Text = "Current Power = " .. game.Players.LocalPlayer.Number.Value
	end)
	
	DownArrow.MouseButton1Click:connect(function()
	power = power - 100
	game.Players.LocalPlayer.Number.Value = game.Players.LocalPlayer.Number.Value - 1
	CurrentPower.Text = "Current Power = " .. game.Players.LocalPlayer.Number.Value
	end)
	end)

end
coroutine.resume(coroutine.create(SCRIPT_DADG89_FAKESCRIPT))
function SCRIPT_NVWH82_FAKESCRIPT() -- FEFlingKill.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = FEFlingKill
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_NVWH82_FAKESCRIPT))
function SCRIPT_HNLA81_FAKESCRIPT() -- FEHax1337.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = FEHax1337
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/WacHseT3'), true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_HNLA81_FAKESCRIPT))
function SCRIPT_AXIJ67_FAKESCRIPT() -- FEHax1337.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = FEHax1337
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_AXIJ67_FAKESCRIPT))
function SCRIPT_IGLT86_FAKESCRIPT() -- FEShutdown.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = FEShutdown
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	error()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_IGLT86_FAKESCRIPT))
function SCRIPT_FAAJ71_FAKESCRIPT() -- FEShutdown.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = FEShutdown
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_FAAJ71_FAKESCRIPT))
function SCRIPT_VNPT66_FAKESCRIPT() -- PhantomForces.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = PhantomForces
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://antinomian-dams.000webhostapp.com/PF/PF_Script.txt", true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_VNPT66_FAKESCRIPT))
function SCRIPT_EZDK83_FAKESCRIPT() -- PhantomForces.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = PhantomForces
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_EZDK83_FAKESCRIPT))
function SCRIPT_ZUFK84_FAKESCRIPT() -- MadCity.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = MadCity
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('http://arilis.win/B1316DFA-DC3A-405D-BF19-99588992BC70.lua'),true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_ZUFK84_FAKESCRIPT))
function SCRIPT_AXHP65_FAKESCRIPT() -- MadCity.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = MadCity
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_AXHP65_FAKESCRIPT))
function SCRIPT_HMPU86_FAKESCRIPT() -- MadCityAutofarm.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = MadCityAutofarm
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	local autofarm = false
	 
	local XPAutoFarmGui = Instance.new("ScreenGui")
	local MainFrame = Instance.new("Frame")
	local Button = Instance.new("TextButton")
	local Deco = Instance.new("TextLabel")
	 
	XPAutoFarmGui.Name = "XPAutoFarmGui"
	XPAutoFarmGui.Parent = game.CoreGui
	 
	MainFrame.Name = "MainFrame"
	MainFrame.Parent = XPAutoFarmGui
	MainFrame.Active = true
	MainFrame.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
	MainFrame.BorderSizePixel = 0
	MainFrame.Draggable = true
	MainFrame.Position = UDim2.new(0.25, 0, 0.25, 0)
	MainFrame.Size = UDim2.new(0.150000006, 0, 0.100000001, 0)
	 
	Button.Name = "Button"
	Button.Parent = MainFrame
	Button.BackgroundColor3 = Color3.new(0, 0, 0)
	Button.BorderSizePixel = 0
	Button.Position = UDim2.new(0.25, 0, 0.400000006, 0)
	Button.Size = UDim2.new(0.5, 0, 0.400000006, 0)
	Button.Font = Enum.Font.SourceSans
	Button.FontSize = Enum.FontSize.Size14
	Button.Text = "OFF"
	Button.TextColor3 = Color3.new(1, 0, 0)
	Button.TextScaled = true
	Button.TextSize = 14
	Button.TextWrapped = true
	 
	Deco.Name = "Deco"
	Deco.Parent = MainFrame
	Deco.BackgroundColor3 = Color3.new(1, 1, 1)
	Deco.BackgroundTransparency = 0.89999997615814
	Deco.BorderSizePixel = 0
	Deco.Size = UDim2.new(1, 0, 0.300000012, 0)
	Deco.Font = Enum.Font.SourceSansBold
	Deco.FontSize = Enum.FontSize.Size14
	Deco.Text = "XP Autofarm"
	Deco.TextColor3 = Color3.new(1, 1, 1)
	Deco.TextScaled = true
	Deco.TextSize = 14
	Deco.TextWrapped = true
	 
	Button.MouseButton1Down:connect(function()
	if autofarm == false then
	autofarm = true
	Button.TextColor3 = Color3.new(0, 1, 0)
	Button.Text = "ON"
	else
	autofarm = false
	Button.TextColor3 = Color3.new(1, 0, 0)
	Button.Text = "OFF"
	end
	end)
	 
	spawn(function()
	while true do
	wait()
	if autofarm == true then
	game.ReplicatedStorage.RemoteFunction:InvokeServer("SetTeam", "Hero")
	game.ReplicatedStorage.RemoteFunction:InvokeServer("SetTeam", "Police")
	game.ReplicatedStorage.RemoteFunction:InvokeServer("SetTeam", "Prisoners")
	wait(1.2)
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-750, 55, -3340))
	wait(1)
	end
	end
	end)
	end)

end
coroutine.resume(coroutine.create(SCRIPT_HMPU86_FAKESCRIPT))
function SCRIPT_FJQQ72_FAKESCRIPT() -- MadCityAutofarm.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = MadCityAutofarm
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_FJQQ72_FAKESCRIPT))
function SCRIPT_CUGR68_FAKESCRIPT() -- SlayingSimulator.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = SlayingSimulator
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet('https://nto.darkdevs.pro/uploads/slaving.txt',true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_CUGR68_FAKESCRIPT))
function SCRIPT_JWRS68_FAKESCRIPT() -- SlayingSimulator.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = SlayingSimulator
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_JWRS68_FAKESCRIPT))
function SCRIPT_DZTQ66_FAKESCRIPT() -- DashingSimulator.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = DashingSimulator
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet('https://nto.darkdevs.pro/uploads/dash.txt',true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_DZTQ66_FAKESCRIPT))
function SCRIPT_KYWE70_FAKESCRIPT() -- DashingSimulator.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = DashingSimulator
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_KYWE70_FAKESCRIPT))
function SCRIPT_ITZX69_FAKESCRIPT() -- ChatBypass.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = ChatBypass
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/ncWQn5CT'),true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_ITZX69_FAKESCRIPT))
function SCRIPT_DNCE80_FAKESCRIPT() -- ChatBypass.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = ChatBypass
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_DNCE80_FAKESCRIPT))
function SCRIPT_GMVQ82_FAKESCRIPT() -- Script.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_GMVQ82_FAKESCRIPT))
function SCRIPT_OZDJ72_FAKESCRIPT() -- Script.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/ncWQn5CT", true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_OZDJ72_FAKESCRIPT))
function SCRIPT_HGRA68_FAKESCRIPT() -- Script_2.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_2
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_HGRA68_FAKESCRIPT))
function SCRIPT_EQQV67_FAKESCRIPT() -- Script_2.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_2
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/pgr6VGkc", true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_EQQV67_FAKESCRIPT))
function SCRIPT_ZZLT83_FAKESCRIPT() -- Script_3.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_3
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_ZZLT83_FAKESCRIPT))
function SCRIPT_ZAET77_FAKESCRIPT() -- Script_3.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_3
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/nMGaEgKj", true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_ZAET77_FAKESCRIPT))
function SCRIPT_DULP75_FAKESCRIPT() -- Script_4.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_4
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_DULP75_FAKESCRIPT))
function SCRIPT_YWMB81_FAKESCRIPT() -- Script_4.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_4
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/7a0YEgv3'),true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_YWMB81_FAKESCRIPT))
function SCRIPT_UKJY79_FAKESCRIPT() -- Script_5.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_5
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_UKJY79_FAKESCRIPT))
function SCRIPT_IOPO76_FAKESCRIPT() -- Script_5.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_5
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/S7HxBkrA'),true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_IOPO76_FAKESCRIPT))
function SCRIPT_BODM66_FAKESCRIPT() -- Script_6.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_6
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_BODM66_FAKESCRIPT))
function SCRIPT_GBEG69_FAKESCRIPT() -- Script_6.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_6
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/yScimcz4",true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_GBEG69_FAKESCRIPT))
function SCRIPT_UYPM75_FAKESCRIPT() -- Script_7.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_7
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_UYPM75_FAKESCRIPT))
function SCRIPT_YJBZ85_FAKESCRIPT() -- Script_7.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_7
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/hvmyZWax", true))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_YJBZ85_FAKESCRIPT))
function SCRIPT_KDMW73_FAKESCRIPT() -- Script_8.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_8
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_KDMW73_FAKESCRIPT))
function SCRIPT_VOCA87_FAKESCRIPT() -- Script_8.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_8
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/G10Whxih'))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_VOCA87_FAKESCRIPT))
function SCRIPT_XRVC66_FAKESCRIPT() -- Script_9.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Script_9
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_XRVC66_FAKESCRIPT))
function SCRIPT_HKOM78_FAKESCRIPT() -- Script_9.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Script_9
	
	
	script.Parent.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/HV3FRYYC'))()
	end)

end
coroutine.resume(coroutine.create(SCRIPT_HKOM78_FAKESCRIPT))
function SCRIPT_GCFF79_FAKESCRIPT() -- DarkMode.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = DarkMode
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.Settings.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
	script.Parent.Parent.Parent.General.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
	script.Parent.Parent.Parent.Remotespy.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
	script.Parent.Parent.Parent.LocalPlayer.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
	script.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
	end)

end
coroutine.resume(coroutine.create(SCRIPT_GCFF79_FAKESCRIPT))
function SCRIPT_CKSU90_FAKESCRIPT() -- DarkMode.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = DarkMode
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_CKSU90_FAKESCRIPT))
function SCRIPT_GQDQ89_FAKESCRIPT() -- Change.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Change
	local btn=script.Parent
	local text = tonumber(script.Parent.Parent.Text)
	
	btn.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.Parent:TweenSize(UDim2.new(text, 'Out', 'Quint', 1))
	end)

end
coroutine.resume(coroutine.create(SCRIPT_GQDQ89_FAKESCRIPT))
function SCRIPT_RLWY89_FAKESCRIPT() -- Change.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Change
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_RLWY89_FAKESCRIPT))
function SCRIPT_KLUT78_FAKESCRIPT() -- RainbowTopBar.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = RainbowTopBar
	local btn=script.Parent
	
	btn.MouseButton1Click:Connect(function()
	script.Parent.Parent.Parent.Top.TopText.LocalScript.Disabled = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_KLUT78_FAKESCRIPT))
function SCRIPT_TDZX90_FAKESCRIPT() -- RainbowTopBar.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = RainbowTopBar
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_TDZX90_FAKESCRIPT))
function SCRIPT_DHWK74_FAKESCRIPT() -- RainbowTopBar.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = RainbowTopBar
	while true do
	Light = script.Parent
	Old = Light.BackgroundColor3
	New = Color3.new(math.random(0,255)/255,math.random(0,255)/255,math.random(0,255)/255)
	
	R = false
	G = false
	B = false
	
	coroutine.resume(coroutine.create(function()
		if New.r > Old.r then
			for i = Old.r, New.r, 2/255 do
				Light.BackgroundColor3 =  Color3.new(i,Light.BackgroundColor3.g,Light.BackgroundColor3.b)
				wait()
			end
		elseif New.r < Old.r then
			for i = Old.r, New.r, -2/255 do
				Light.BackgroundColor3 =  Color3.new(i,Light.BackgroundColor3.g,Light.BackgroundColor3.b)
				wait()
			end
		end
		R = true
	end))
	
	coroutine.resume(coroutine.create(function()
		if New.g > Old.g then
			for i = Old.g,New.g,2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,i,Light.BackgroundColor3.b)
				wait()
			end
		else
			for i = Old.g,New.g,-2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,i,Light.BackgroundColor3.b)
				wait()
			end
		end
		G = true
	end))
	
	coroutine.resume(coroutine.create(function()
		if New.b > Old.b then
			for i = Old.b,New.b,2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,Light.BackgroundColor3.g,i)
				wait()
			end
		else
			for i = Old.b,New.b,-2/255 do
				Light.BackgroundColor3 =  Color3.new(Light.BackgroundColor3.r,Light.BackgroundColor3.g,i)
				wait()
			end
		end
		B = true
	end))
	
	repeat wait(1/30) until R == true and G == true and B == true
	
	end

end
coroutine.resume(coroutine.create(SCRIPT_DHWK74_FAKESCRIPT))
function SCRIPT_RHVY77_FAKESCRIPT() -- Load.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Load
	local undetectable = "vi install undetectable - 0, 5"
	local advanced = "vi install switch advanced - *"
	local design2 = "vi install override currentDesign * betaDesign"
	local design3 = "vi install client data transfer to server - 3, 2"
	
	
	script.Parent.MouseButton1Click:Connect(function()
	if script.Parent.Parent.Text == undetectable or advanced or design2 or design3 then
	script.Parent.Parent.Text = "Successfully ran features!"
	else
	script.Parent.Parent.Text = "Unknown install command."
	end
	end)

end
coroutine.resume(coroutine.create(SCRIPT_RHVY77_FAKESCRIPT))
function SCRIPT_KMTE80_FAKESCRIPT() -- Fire.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Fire
	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
	local abc = Instance.new("Fire")
	abc.Parent = player.Character.Torso
	end)

end
coroutine.resume(coroutine.create(SCRIPT_KMTE80_FAKESCRIPT))
function SCRIPT_CGCW73_FAKESCRIPT() -- Fire.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Fire
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_CGCW73_FAKESCRIPT))
function SCRIPT_YARS67_FAKESCRIPT() -- Sparkes.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Sparkes
	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
	local abc = Instance.new("Sparkles")
	abc.Parent = player.Character.Torso
	end)

end
coroutine.resume(coroutine.create(SCRIPT_YARS67_FAKESCRIPT))
function SCRIPT_BWFI77_FAKESCRIPT() -- Sparkes.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Sparkes
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_BWFI77_FAKESCRIPT))
function SCRIPT_EKPE69_FAKESCRIPT() -- Fly.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Fly
	script.Parent.MouseButton1Click:Connect(function()
	 repeat wait()
	   until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local flying = true
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
coroutine.resume(coroutine.create(SCRIPT_EKPE69_FAKESCRIPT))
function SCRIPT_LTKQ85_FAKESCRIPT() -- Fly.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Fly
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_LTKQ85_FAKESCRIPT))
function SCRIPT_XLRM89_FAKESCRIPT() -- Walkspeed.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Walkspeed
	script.Parent.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_XLRM89_FAKESCRIPT))
function SCRIPT_MJFJ90_FAKESCRIPT() -- Walkspeed.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Walkspeed
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_MJFJ90_FAKESCRIPT))
function SCRIPT_DGCM89_FAKESCRIPT() -- JumpPower.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = JumpPower
	script.Parent.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_DGCM89_FAKESCRIPT))
function SCRIPT_ZPAG73_FAKESCRIPT() -- JumpPower.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = JumpPower
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_ZPAG73_FAKESCRIPT))
function SCRIPT_IKID86_FAKESCRIPT() -- Gravity.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Gravity
	script.Parent.MouseButton1Click:Connect(function()
	game.Workspace.Gravity = 52
	end)

end
coroutine.resume(coroutine.create(SCRIPT_IKID86_FAKESCRIPT))
function SCRIPT_XXRL75_FAKESCRIPT() -- Gravity.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Gravity
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_XXRL75_FAKESCRIPT))
function SCRIPT_PNSL79_FAKESCRIPT() -- Noclip.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Noclip
	script.Parent.MouseButton1Click:Connect(function()
	local noclip = true;
	local char = game.Players.LocalPlayer.Character while true do if noclip == true then for _,v in pairs(char:children()) do pcall(function() if v.className == "Part" then v.CanCollide = false elseif v.ClassName == "Model" then v.Head.CanCollide = false end end) end end game:service("RunService").Stepped:wait() end
	end)

end
coroutine.resume(coroutine.create(SCRIPT_PNSL79_FAKESCRIPT))
function SCRIPT_XIST67_FAKESCRIPT() -- Noclip.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = Noclip
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_XIST67_FAKESCRIPT))
function SCRIPT_XQTS90_FAKESCRIPT() -- FEInvisible.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = FEInvisible
	script.Parent.MouseButton1Click:Connect(function()
	
	Local = game:GetService('Players').LocalPlayer
	Char  = Local.Character
	touched,tpdback = false, false
	Local.CharacterAdded:connect(function(char)
	    if script.Disabled ~= true then
	        wait(.25)
	        loc = Char.HumanoidRootPart.Position
	        Char:MoveTo(box.Position + Vector3.new(0,.5,0))
	    end
	end)
	game:GetService('UserInputService').InputBegan:connect(function(key)
	    if key.KeyCode == Enum.KeyCode.Equals then
	        if script.Disabled ~= true then
	            script.Disabled = true
	            print'you may re-execute'
	        end
	    end
	end)
	box = Instance.new('Part',workspace)
	box.Anchored = true
	box.CanCollide = true
	box.Size = Vector3.new(10,1,10)
	box.Position = Vector3.new(0,10000,0)
	box.Touched:connect(function(part)
	    if (part.Parent.Name == Local.Name) then
	        if touched == false then
	            touched = true
	            function apply()
	                if script.Disabled ~= true then
	                    no = Char.HumanoidRootPart:Clone()
	                    wait(.25)
	                    Char.HumanoidRootPart:Destroy()
	                    no.Parent = Char
	                    Char:MoveTo(loc)
	                    touched = false
	                end end
	            if Char then
	                apply()
	            end
	        end
	    end
	end)
	repeat wait() until Char
	loc = Char.HumanoidRootPart.Position
	Char:MoveTo(box.Position + Vector3.new(0,.5,0))
	end)

end
coroutine.resume(coroutine.create(SCRIPT_XQTS90_FAKESCRIPT))
function SCRIPT_FGNL76_FAKESCRIPT() -- FEInvisible.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = FEInvisible
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_FGNL76_FAKESCRIPT))
function SCRIPT_QBDU70_FAKESCRIPT() -- god.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = god
	script.Parent.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid:Remove()
	Instance.new("Humanoid", game.Players.LocalPlayer.Character)
	end)

end
coroutine.resume(coroutine.create(SCRIPT_QBDU70_FAKESCRIPT))
function SCRIPT_HNMO90_FAKESCRIPT() -- god.Effect 
	local script = Instance.new('LocalScript')
	script.Parent = god
	script.Parent.MouseButton1Down:Connect(function(X, Y)
	local C = Instance.new('ImageLabel', script.Parent)
	C.BackgroundTransparency = 1
	C.Position = UDim2.new(0, X - 0, 0, Y - 35) - UDim2.new(0, script.Parent.AbsolutePosition.X, 0, script.Parent.AbsolutePosition.Y)
	C.Size = UDim2.new(0, 0, 0, 0)
	C.Image = 'rbxassetid://200182847'
	C.ImageColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
	C.Name = 'Circle'
	C:TweenSizeAndPosition(UDim2.new(0, 500, 0, 500), C.Position - UDim2.new(0, 250, 0, 250), 'Out', 'Quart', 2.5)
	for i = 0, 1, 0.03 do
	C.ImageTransparency = i
	game:GetService('RunService').RenderStepped:wait()
	end
	C:destroy()
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_HNMO90_FAKESCRIPT))
function SCRIPT_AHEI77_FAKESCRIPT() -- MainGUI.Toggle 
	local script = Instance.new('LocalScript')
	script.Parent = MainGUI
	local getMouse = game.Players.LocalPlayer:GetMouse()
	
	getMouse.KeyDown:Connect(function(key)
	if key == 'p' then
	if script.Parent.Visible == true then
		script.Parent.Visible = false;
	else
		script.Parent.Visible = true;
	end
	end
	end)

end
coroutine.resume(coroutine.create(SCRIPT_AHEI77_FAKESCRIPT))
function SCRIPT_CXTJ79_FAKESCRIPT() -- Access.Access 
	local script = Instance.new('LocalScript')
	script.Parent = Access
	local login = script.Parent.Parent.Parent.Login
	local password = script.Parent.Parent.Parent.Password
	local topText = script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText
	
	function effect()
	script.Parent.Parent.Visible = false;
	script.Parent.Parent.Parent.Login.Visible = false;
	script.Parent.Parent.Parent.Password.Visible = false;
	script.Parent.Parent.Parent.Spin.Visible = true;
	script.Parent.Parent.Parent.TextHit.Visible = true;
	wait(5)
	script.Parent.Parent.Parent.Visible = false;
	end
	
	local admin = {
					"admin",
					1,
					"admin" 
	}
	local JesusBinOLaden = {
		"JesusBinOLaden",
		2,
		"epicgamer"
	}
	local wafoocool = {
		'wafoocool',
		3,
		'young123'
	}
	local YungMakaveli = {
		'YungMakaveli',
		4,
		'tati225'
	}
	local StretchzX = {
		'StretchzX',
		5,
		'45er4545'
	}
	local watchcorporation = {
		'watchcorporation',
		6,
		'5267'
	}
	local KyrieIrving = {
		'KyrieIrving23302',
		7,
		'ILVFRVR'
	}
	local wout = {
		'wout712',
		8,
		'yeeterooni666'
	}
	local tail = {
		'Tail41',
		9,
		'qwert0101'
	}
	local IAmAPanda = {
		'IAmAPandax2',
		10,
		'youssif12'
	}
	local GhostzBunny = {
		'GhostzBunny',
		11,
		'Mysterious1'
	}
	local thisaccountisrare = {
		'thisaccountisrare2',
		12,
		'ArigatoGyro'
	}
	local UnDefined = {
		'IIlIIIlIIlIllIlllIII',
		13,
		'blue0831good'
	}
	local AnotherOne = {
		'MhycoSuello_YT',
		14,
		'ExodusZero'
	}
	local in_sin = {
		'in_sin',
		15,
		'kidscan98765'
	}
	local GrenMods = {
		'Nurarihyon',
		16,
		'2928203'
		
	}
	local specialPerson = {
		'fx2c0neqw_2mfdsgqrlp',
		17,
		'Wyuro21'
	}
	local TeamFlam = {
		'TeamFlam3_YT',
		18,
		'Byronkeepitreal'
	}
	local manly = {
		'manly76',
		19,
		'yTrFgSvV'
	}
	local Hot_ColdTodoroki = {
		'Hot_ColdTodoroki',
		20,
		'daddy5'
	}
	local Chromiuc = {
		'Chromiuc',
		21,
		'yourmomok'
	}
	local xxLiamAvnixx = {
		'xxLiamAvnixx',
		22,
		'mypassisliam'
	}
	local Happy = {
		'Happy74',
		23,
		'faggot'
	}
	local Mysteriousameo = {
		'Mysteriousameo',
		24,
		'Lolxdack'
	}
	local Ashgreenninja = {
		'Ashgreenninja',
		25,
		'RobloxIsGae'
	}
	local yanzitu = {
		'suckmyballs',
		26,
		'fuckoff'
	}
	local jhow = {
		'jhow12345',
		27,
		'feijao12'
	}
	local emincanreyiz = {
		'emincanreyiz01',
		28,
		'urmomgayedchrome'
	}
	local jdroob = {
		'jdroob',
		29,
		'HackingIsGood123'
	}
	local hadiizan = {
		'hadiizan36',
		30,
		'Nobodycanguessthispassword'
	}
	local lukewentink = {
		'lukewentink',
		31,
		'12345'
	}
	local Kabuto = {
		'Kabuto22',
		32,
		'bao1234'
	}
	local Kabuto2 = {
		'kikilo76',
		33,
		'Divise'
	}
	local Identity = {
		'Identity7',
		34,
		'password123'
	}
	local F11nDerin = {
		'F11nDerin',
		35,
		'9wKrawkw9'
	} 
	local MateusBr020203 = {
		'MateusBr020203',
		36,
		'MecTrefe28192001'
	}
	local HomicidalSprayer = {
		'HomicidalSprayer',
		37,
		'TheBiggestFaggot13'
	}
	local account123 = {
		'3xI8',
		38,
		'Etap_OP'
	}
	local im_scripter = {
		'im_scripter',
		39,
		'robloxsucks'
	}
	local nerfine = {
		'a',
		40,
		'b'
	}
	local StereoTIP4IK = {
		'StereoTIP4IK',
		41,
		'%NFbBAj+C9SG=uuj'
	}
	local gesn = {
		'gesn',
		42,
		'123kim123123'
	}
	local Soursupersoldier2 = {
		'Soursupersoldier2',
		43,
		'Alritr'
	}
	local hangmeirl = {
		'hangmeirl',
		44,
		'ComdeyRussell'
	}
	local Connor13506 = {
		'Connor13506',
		45,
		'ReignAdmin'
	}
	
	
	
	script.Parent.MouseButton1Click:Connect(function()
	if login.Text == "admin" and password.Text == "admin" then
		if game.Players.LocalPlayer.Name == "MyAccountIsBannedRip" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. admin[1] .. ", Id = " .. admin[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
		end
	end
	if login.Text == "JesusBinOLaden" and password.Text == "epicgamer" then
	if game.Players.LocalPlayer.Name == "JesusBinOLaden" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. JesusBinOLaden[1] .. ", Id = " .. JesusBinOLaden[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "wafoocool" and password.Text == "young123" then
	if game.Players.LocalPlayer.Name == "wafoocool" or "gfmf" or "Reset8278942" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. wafoocool[1] .. ", Id = " .. wafoocool[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "YungMakaveli" and password.Text == "tati225" then
	if game.Players.LocalPlayer.Name == "YungMakaveli" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. YungMakaveli[1] .. ", Id = " .. YungMakaveli[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "StretchzX" and password.Text == "45er4545" then
	if game.Players.LocalPlayer.Name == "StretchzX" or "gfmf" or "streetsgettingbluat" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. StretchzX[1] .. ", Id = " .. StretchzX[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "watchcorporation" and password.Text == "ThisIsABannedUser0122" then
	if game.Players.LocalPlayer.Name == "watchcorporation" or "gfmf" or "dunobna" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. watchcorporation[1] .. ", Id = " .. watchcorporation[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "KyrieIrving23302" and password.Text == "ILVFRVR" then
	if game.Players.LocalPlayer.Name == "KyrieIrving23302" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. KyrieIrving[1] .. ", Id = " .. KyrieIrving[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "wout712" and password.Text == "yeeterooni666" then
	if game.Players.LocalPlayer.Name == "KyrieIrving23302" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. wout[1] .. ", Id = " .. wout[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Tail41" and password.Text == "qwert0101" then
	if game.Players.LocalPlayer.Name == "Tail41" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. tail[1] .. ", Id = " .. tail[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "IAmAPandax2" and password.Text == "youssif12" then
	if game.Players.LocalPlayer.Name == "IAmAPandax2" or "gfmf" or "IAmAPandax4" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. IAmAPanda[1] .. ", Id = " .. IAmAPanda[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "GhostzBunny" and password.Text == "Mysterious1" then
	if game.Players.LocalPlayer.Name == "GhostzBunny" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. GhostzBunny[1] .. ", Id = " .. GhostzBunny[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "thisaccountisrare2" and password.Text == "ArigatoGyro" then
	if game.Players.LocalPlayer.Name == "thisaccountisrare2" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. thisaccountisrare[1] .. ", Id = " .. thisaccountisrare[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "IIlIIIlIIlIllIlllIII" and password.Text == "blue0831good" then
	if game.Players.LocalPlayer.Name == "IIlIIIlIIlIllIlllIII" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. UnDefined[1] .. ", Id = " .. UnDefined[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "MhycoSuello_YT" and password.Text == "ExodusZero" then
	if game.Players.LocalPlayer.Name == "MhycoSuello_YT" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. AnotherOne[1] .. ", Id = " .. AnotherOne[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "in_sin" and password.Text == "kidscan98765" then
	if game.Players.LocalPlayer.Name == "in_sin" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. in_sin[1] .. ", Id = " .. in_sin[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Nurarihyon" and password.Text == "2928203" then
	if game.Players.LocalPlayer.Name == "Nurihyon" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Nurihyon[1] .. ", Id = " .. Nurihyon[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "fx2c0neqw_2mfdsgqrlp" and password.Text == "Wyuro21" then
	if game.Players.LocalPlayer.Name == "fx2c0neqw_2mfdsgqrlp" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. specialPerson[1] .. ", Id = " .. specialPerson[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "TeamFlam3_YT" and password.Text == "Byronkeepitreal" then
	if game.Players.LocalPlayer.Name == "TeamFlam3_YT" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. TeamFlam[1] .. ", Id = " .. TeamFlam[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "manly76" and password.Text == "yTrFgSvV" then
	if game.Players.LocalPlayer.Name == "manly76" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. manly[1] .. ", Id = " .. manly[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Hot_ColdTodoroki" and password.Text == "daddy5" then
	if game.Players.LocalPlayer.Name == "Hot_ColdTodoroki" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Hot_ColdTodoroki[1] .. ", Id = " .. Hot_ColdTodoroki[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Chromiuc" and password.Text == "yourmomok" then
	if game.Players.LocalPlayer.Name == "Chromiuc" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Chromiuc[1] .. ", Id = " .. Chromiuc[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "xxLiamAvnixx" and password.Text == "mypassisliam" then
	if game.Players.LocalPlayer.Name == "xxLiamAvnixx" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. xxLiamAvnixx[1] .. ", Id = " .. xxLiamAvnixx[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Happy74" and password.Text == "faggot" then
	if game.Players.LocalPlayer.Name == "Happy74" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Happy[1] .. ", Id = " .. Happy[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Mysteriousameo" and password.Text == "Lolxdack" then
	if game.Players.LocalPlayer.Name == "Mysteriousameo" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Mysteriousameo[1] .. ", Id = " .. Mysteriousameo[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Ashgreenninja14" and password.Text == "RobloxIsGae" then
	if game.Players.LocalPlayer.Name == "Ashgreenninja14" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Ashgreenninja[1] .. ", Id = " .. Ashgreenninja[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "suckmyballs" and password.Text == "fuckoff" then
	if game.Players.LocalPlayer.Name == "Nzxke" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, Nzxke"
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "jhow12345" and password.Text == "feijao12" then
	if game.Players.LocalPlayer.Name == "jhow12345" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. jhow[1] .. ", Id = " .. jhow[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "emincanreyiz01" and password.Text == "urmomgayedchrome" then
	if game.Players.LocalPlayer.Name == "emincanreyiz01" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. emincanreyiz[1] .. ", Id = " .. emincanreyiz[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "jdroob" and password.Text == "HackingIsGood123" then
	if game.Players.LocalPlayer.Name == "jdroob" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. jdroob[1] .. ", Id = " .. jdroob[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "hadiizan36" and password.Text == "Nobodycanguessthispassword" then
	if game.Players.LocalPlayer.Name == "hadiizan36" or "gfmf" or "Natural_Fart" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. hadiizan[1] .. ", Id = " .. hadiizan[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "lukewentink" and password.Text == "12345" then
	if game.Players.LocalPlayer.Name == "lukewentink" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. lukewentink[1] .. ", Id = " .. lukewentink[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Kabuto22" and password.Text == "bao1234" then
	if game.Players.LocalPlayer.Name == "Kabuto22" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Kabuto[1] .. ", Id = " .. Kabuto[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "LafonduDeSUISSE" and password.Text == "echo.eeee" then
	if game.Players.LocalPlayer.Name == "LafonduDeSUISSE" or "jeanyvesdelacompta" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Kabuto2[1] .. ", Id = " .. Kabuto[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Identity7" and password.Text == "password123" then
	if game.Players.LocalPlayer.Name == "jeanyvesdelacompta" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Identity[1] .. ", Id = " .. Identity[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "F11nDerin" and password.Text == "9wKrawkw9" then
	if game.Players.LocalPlayer.Name == "Kabuto22" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. F11nDerin[1] .. ", Id = " .. F11nDerin[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "MateusBr020203" and password.Text == "MecTrefe28192001" then
	if game.Players.LocalPlayer.Name == "MateusBr020203" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. MateusBr020203[1] .. ", Id = " .. MateusBr020203[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "HomicidalSprayer" and password.Text == "TheBiggestFaggot13" then
	if game.Players.LocalPlayer.Name == "HomicidalSprayer" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. HomicidalSprayer[1] .. ", Id = " .. HomicidalSprayer[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "3xI8" and password.Text == "Etap_OP" then
	if game.Players.LocalPlayer.Name == "3xI8" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. account123[1] .. ", Id = " .. account123[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "im_scripter" and password.Text == "robloxsucks" then
	if game.Players.LocalPlayer.Name == "im_scripter" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. im_scripter[1] .. ", Id = " .. im_scripter[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "a" and password.Text == "b" then
	if game.Players.LocalPlayer.Name == "nrbad" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, nrbad"
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "StereoTIP4IK" and password.Text == "dimon2004" then
	if game.Players.LocalPlayer.Name == "StereoTIP4IK" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. StereoTIP4IK[1] .. ", Id = " .. StereoTIP4IK[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "gesn" and password.Text == "123kim123123" then
	if game.Players.LocalPlayer.Name == "Kabuto22" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. gesn[1] .. ", Id = " .. gesn[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "Soursupersoldier2" and password.Text == "Alritr" then
	if game.Players.LocalPlayer.Name == "Soursupersoldier2" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Soursupersoldier2[1] .. ", Id = " .. Soursupersoldier2[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "hangmeirl" and password.Text == "ComdeyRusse11" then
	if game.Players.LocalPlayer.Name == "hangmeirl" or "gfmf" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. hangmeirl[1] .. ", Id = " .. hangmeirl[2]
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	if login.Text == "" and password.Text == "" then
	if game.Players.LocalPlayer.Name == "Jarsa132PL" or "jarsa132" then
		script.Parent.Parent.Parent.Parent.MainGUI.Top.TopText.ID.Text = "Hello, " .. Jarsa132 .. ", Id = " .. Jarsa132
		effect()
		script.Parent.Parent.Parent.Parent.MainGUI.Visible = true;
		else
		script.Parent.Text = "Invalid, try again."
		wait(3)
		script.Parent.Text = "Access"
	end
	end
	
	end)

end
coroutine.resume(coroutine.create(SCRIPT_CXTJ79_FAKESCRIPT))
function SCRIPT_ZUPZ83_FAKESCRIPT() -- ForgotPassword.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = ForgotPassword
	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Info.Visible = true
	end)

end
coroutine.resume(coroutine.create(SCRIPT_ZUPZ83_FAKESCRIPT))
function SCRIPT_UWXB80_FAKESCRIPT() -- Info.drag 
	local script = Instance.new('LocalScript')
	script.Parent = Info
	script.Parent.Draggable = true;

end
coroutine.resume(coroutine.create(SCRIPT_UWXB80_FAKESCRIPT))
function SCRIPT_KCPQ68_FAKESCRIPT() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = TextButton
	script.Parent.MouseButton1Click:Connect(function()
	script.Parent.Parent.Visible = false;
	end)

end
coroutine.resume(coroutine.create(SCRIPT_KCPQ68_FAKESCRIPT))
function SCRIPT_CWGH75_FAKESCRIPT() -- LoginGUI.drag 
	local script = Instance.new('LocalScript')
	script.Parent = LoginGUI
	print("Loaded Reign V1.6")
	script.Parent.Draggable = true;
	

end
coroutine.resume(coroutine.create(SCRIPT_CWGH75_FAKESCRIPT))
function SCRIPT_TOGI67_FAKESCRIPT() -- Spin.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = Spin
	repeat script.Parent.Rotation = script.Parent.Rotation + 2 wait() until script.Parent.Parent.Visible == false;

end
coroutine.resume(coroutine.create(SCRIPT_TOGI67_FAKESCRIPT))
function SCRIPT_BTOH90_FAKESCRIPT() -- TextHit.LocalScript 
	local script = Instance.new('LocalScript')
	script.Parent = TextHit
	local random = math.random(1,5)
	
	if random == 1 then
	script.Parent.Text = "vi#9292 is a psycho nerd"
	elseif random == 2 then
	script.Parent.Text = "rzeu farted on this gui."
	elseif random == 3 then
	script.Parent.Text = "how to execute this?"
	elseif random == 4 then
	script.Parent.Text = "bumbumbumbumbum"
	elseif random == 5 then
	script.Parent.Text = "reeeeeee"
	end

end
coroutine.resume(coroutine.create(SCRIPT_BTOH90_FAKESCRIPT))
