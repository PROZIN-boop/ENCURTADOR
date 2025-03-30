local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()


local Window = Rayfield:CreateWindow({
Name = "Vano | Universal",
LoadingTitle = "Vano Universal",
LoadingSubtitle = "by Prozin",
ConfigurationSaving = {
Enabled = true,
FolderName = nil, -- Create a custom folder for your hub/game
FileName = "Big Hub"
},
        Discord = {
        Enabled = true,
        Invite = "5tHVrWChDh", -- The Discord invite code, do not include discord.gg/
        RememberJoins = true -- Set this to false to make them join the discord every time they load it up
        },
KeySystem = true, -- Set this to true to use our key system
KeySettings = {
Title = "Key System | Vano",
Subtitle = "Key System",
Note = "Work.ink (https://workink.net/1YR5/mlx0u0zj)",
FileName = "VanoKey",
SaveKey = true,
GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
Key = "https://pastebin.com/raw/GHuiUc3i"
}
})

local Tab = Window:CreateTab("Blox Fruits", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
Name = "W-Azure",
Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
end,
})

local Button = Tab:CreateButton({
Name = "Speed X Hub",
Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
end,
})

local Button = Tab:CreateButton({
Name = "Kncrypt",
Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/Kncrypt/refs/heads/main/sources/BloxFruit.lua"))()
end,
})

local Button = Tab:CreateButton({
Name = "HoHo Hub",
Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()
end,
})

local Button = Tab:CreateButton({
Name = "Banana Hub",
Callback = function()
repeat wait() until game:IsLoaded() and game.Players.LocalPlayer 
getgenv().Key = "Put your Key here" 
loadstring(game:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BananaHub.lua"))()
end,
})

local Button = Tab:CreateButton({
Name = "Alchemy Hub",
Callback = function()
loadstring(game:HttpGet("https://scripts.alchemyhub.xyz"))()
end,
})

local Tab = Window:CreateTab("King Legacy", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
Name = "Fazium Hub",
Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ZaRdoOx/Loader/main/PlatiniumLoader"))()
end,
})

local Button = Tab:CreateButton({
Name = "OMG Hub",
Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Omgshit/Scripts/main/MainLoader.lua"))()
end,
})

local Button = Tab:CreateButton({
Name = "BlackRose",
Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ViolentRose/BlackRose/main/ViolentGameList.lua"))()
end,
})

local Button = Tab:CreateButton({
Name = "Nil Hub",
... (150 linhas)
