# my-hub


local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Sigma Boy hub",
   LoadingTitle = "Sup Biggie",
   LoadingSubtitle = "...",
   ConfigurationSaving = {
      Enabled = falase,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Sigma Boy Hub Key System",
      Subtitle = "The Smallest Hub Ever",
      Note = "Key = raw link in dc/discord.",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"https://pastebin.com/raw/Lknxb5G4"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab("Basic Scripts 🗿", nill) -- Title, Image
local MainSection = MainTab:CreateSection("Main")

Rayfield:Notify({
   Title = "noice it loaded",
   Content = "nah i'd win.",
   Duration = 6.5,
   Image = nill,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "OKAY",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})

local Button = MainTab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
      loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
   end,
})

local Slider = MainTab:CreateSlider({
   Name = "Gotta GO FAST",
   Range = {0, 100},
   Increment = 10,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "Slider1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayers.Character.Humaniod.Walkspeed = (Value)
   end,
})

local Button = MainTab:CreateButton({
   Name = "Kade Hub",
   Callback = function()
      --[[
    
]]
----<< LOADER >> -----
if getgenv().KadeHubLoaded ~= true then
    getgenv().KadeHubLoaded = true
   loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/Work/main/latest.lua"))()
else
    game.StarterGui:SetCore("SendNotification",  { Title = "KadeHub"; Text = "KadeHub is already executed!"; Icon = "rbxassetid://17893547380"; Duration = 15; })
end
   end,
})

local Tab = Window:CreateTab("for moblie", nill) -- Title, Image
local Section = Tab:CreateSection("Main")

local Button = Tab:CreateButton({
   Name = "speed",
 Callback = function()
       local a = game:GetService("Players").LocalPlayer.Character or game:GetService("Players").LocalPlayer.CharacterAdded:wait()

while wait(1) do
    local b = a:FindFirstChildOfClass("Humanoid") or a:FindFirstChildOfClass("AnimationController")
    if not b or not a then continue end
    for c, d in next, b:GetPlayingAnimationTracks() do
        d:AdjustSpeed(33456666776554443345)
    end
end 
   end,
})

local Button = Tab:CreateButton({
   Name = "KJ Script By Me",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/KjV2/refs/heads/main/KJ%20moveset", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Shinji",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/Shinji", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "CT2",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/CLONE-TYCOON/refs/heads/main/Money", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Prizz admin (PRISON LIFE SCRIPT)",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/Prizz/refs/heads/main/Prizz.Lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Change m9 name",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/Prison-life/refs/heads/main/CHANGE%20m9%20WEAPON%20name", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Change ak name",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/Prison-life/refs/heads/main/Change%20Ak%20weapon.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "change rem name",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/Prison-life/refs/heads/main/Change%20rem%20name.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fling gui",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/Fling%20script", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "real",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/Chat", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "kj ufw anim",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/KjV2/refs/heads/main/Kj%20ufw%20anim.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "D E A T H",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/DEATH", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Sukuna",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/KjV2/refs/heads/main/Sukuna", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "TCO",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/Tco", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Garou To Sukuna",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/Moveset/refs/heads/main/Garou%20To%20Sukuna", true))()
   end,
})

local Tab = Window:CreateTab("Prison Life", nill) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Criminal yourself",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/Criminal.lua", true))()
   end,
})

local Tab = Window:CreateTab("Knock The Blocks 🅱️🅾️🅾️🅱️S", nill) -- Title, Image

local Button = Tab:CreateButton({
   Name = "InstaWin",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/SigmaOnTheSigma/kj-hub/refs/heads/main/TeleportToWin.lua", true))()
   end,
})
