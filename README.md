tkotn
--RF LIB --

--this was entirely made by Hasona5000



local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))() 

local Window = Rayfield:CreateWindow({
    Name = "Script Engine",
    LoadingTitle = "Hasona5000",
    LoadingSubtitle = "Loading. . .",
    ConfigurationSaving = {
       Enabled = true,
       FolderName = nil, 
       FileName = "0Scripthub tk"
    },

    
    KeySystem = false,
    KeySettings = {
       Title = "Key System",
       Subtitle = "Enter your key",
       Note = "123",
       FileName = "Key", 
       SaveKey = true, 
       GrabKeyFromSite = false, 
       Key = {"123"} 
    }
 })
 


 local HomeTab = Window:CreateTab("Home", 4483362458)

 local SectionH1 = HomeTab:CreateSection("Main")


local Button = HomeTab:CreateButton({
   Name = "N/A",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
   end,
})

 local Button = HomeTab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
       loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "Orca Hub X",
   Callback = function()
       loadstring(game:HttpGet('https://pastebin.com/raw/PuFbZQFp'))()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "Fly Gui V3",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "Reach",
   Callback = function()
       loadstring(game:HttpGet("https://pastebin.com/raw/CpFsn2bJ"))()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "Vape V4",
   Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "Netless",
   Callback = function()
       loadstring(game:HttpGet(('https://pastebin.com/raw/Cu7bKQWN'),true))()
   end,
})


local SectionH4 = HomeTab:CreateSection("Movement")



local Slider = HomeTab:CreateSlider({
   Name = "WalkSpeed",
   Range = {16, 550},
   Increment = 1,
   Suffix = "WalkSpeed",
   CurrentValue = 16,
   Flag = "WsSlider1", 
   Callback = function(Value)
       game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
   end,
})


local Slider = HomeTab:CreateSlider({
   Name = "JumpPower",
   Range = {50, 550},
   Increment = 1,
   Suffix = "JumpPower",
   CurrentValue = 50,
   Flag = "JpSlider2", 
   Callback = function(Value)
       game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
   end,
})

local Input = HomeTab:CreateInput({
   Name = "Walkspeed",
   PlaceholderText = "16-inf",
   RemoveTextAfterFocusLost = true,
   Callback = function(Text)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Text)
   end,
})

local Input = HomeTab:CreateInput({
   Name = "JumpPower",
   PlaceholderText = "50-inf",
   RemoveTextAfterFocusLost = true,
   Callback = function(Text)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = (Text)
   end,
})

local SectionH5 = HomeTab:CreateSection("LocalPlayer")



 local Button = HomeTab:CreateButton({
   Name = "ForceReset",
   Callback = function()
       game.Players.LocalPlayer.Character.Head:Destroy()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "AntiAfk",
   Callback = function()
       loadstring(game:HttpGet("https://pastebin.com/raw/7a0KairA"))()
   end,
})


local SectionH6 = HomeTab:CreateSection("Utility")

local Button = HomeTab:CreateButton({
   Name = "F3X",
   Callback = function()
      loadstring(game:GetObjects("rbxassetid://6695644299")[1].Source)()
   end,
})

local Button = HomeTab:CreateButton({
   Name = "Click TP",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/E0mTN6L6"))()
   end,
})


local Button = HomeTab:CreateButton({
   Name = "B-Tools (Client)",
   Callback = function()
      loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/BTools.txt"))()
   end,
})


local Button = HomeTab:CreateButton({
   Name = "X-RAY (X)",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/d7swJz3R"))()
   end,
})







 local MainTab = Window:CreateTab("NSM", 4483362458)

 local Section = MainTab:CreateSection("Main")

 local MainButton = MainTab:CreateButton({
   Name = "N/A",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
   end,
})


  local Button = MainTab:CreateButton({
    Name = "Infinite Yield",
    Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    end,
 })


 local Button = MainTab:CreateButton({
    Name = "Orca Hub X",
    Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/PuFbZQFp'))()
    end,
 })

 
 local MainButton = MainTab:CreateButton({
    Name = "Fly Gui V3",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
    end,
 })

 
 local MainButton = MainTab:CreateButton({
    Name = "Reach",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/CpFsn2bJ"))()
    end,
 })

 
 
 
 local MainButton = MainTab:CreateButton({
    Name = "Netless",
    Callback = function()
        loadstring(game:HttpGet(('https://pastebin.com/raw/Cu7bKQWN'),true))()
    end,
 })

 

 local MainButton = MainTab:CreateButton({
    Name = "Vape V4",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
    end,
 })


 local PlayerTab = Window:CreateTab("Local", 4483362458)

 local MVSection = PlayerTab:CreateSection("Movement")
 local Slider = PlayerTab:CreateSlider({
    Name = "WalkSpeed",
    Range = {16, 550},
    Increment = 1,
    Suffix = "WalkSpeed",
    CurrentValue = 16,
    Flag = "WsSlider1", 
    Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
    end,
 })



 local Slider = PlayerTab:CreateSlider({
    Name = "JumpPower",
    Range = {50, 550},
    Increment = 1,
    Suffix = "JumpPower",
    CurrentValue = 50,
    Flag = "JpSlider2", 
    Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
    end,
 })
 

 local Input = PlayerTab:CreateInput({
   Name = "Walkspeed",
   PlaceholderText = "16-inf",
   RemoveTextAfterFocusLost = true,
   Callback = function(Text)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Text)
   end,
})

local Input = PlayerTab:CreateInput({
   Name = "JumpPower",
   PlaceholderText = "50-inf",
   RemoveTextAfterFocusLost = true,
   Callback = function(Text)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = (Text)
   end,
})


 local PlayerSection = PlayerTab:CreateSection("LocalPlayer")

 local Button = PlayerTab:CreateButton({
   Name = "ForceReset",
   Callback = function()
       game.Players.LocalPlayer.Character.Head:Destroy()
   end,
})

local Button = PlayerTab:CreateButton({
   Name = "AntiAfk",
   Callback = function()
       loadstring(game:HttpGet("https://pastebin.com/raw/7a0KairA"))()
   end,
})


local UtilitySection = PlayerTab:CreateSection("Utility")


local Button = PlayerTab:CreateButton({
   Name = "ESP",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/pcGXxtqW"))()
   end,
})



local Button = PlayerTab:CreateButton({
   Name = "F3X",
   Callback = function()
      loadstring(game:GetObjects("rbxassetid://6695644299")[1].Source)()
   end,
})

local Button = PlayerTab:CreateButton({
   Name = "Click TP",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/E0mTN6L6"))()
   end,
})


local Button = PlayerTab:CreateButton({
   Name = "B-Tools (Client)",
   Callback = function()
      loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/BTools.txt"))()
   end,
})


local Button = PlayerTab:CreateButton({
   Name = "X-RAY (X)",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/d7swJz3R"))()
   end,
})






local GamesTab = Window:CreateTab("LSD", 4483362458)


local DestroyTab = Window:CreateTab("Destroy", 14447833297)











local HubsTab = Window:CreateTab("Hubs", 4483362458)



local Button = HubsTab:CreateButton({
   Name = "Oasis Hub X",
   Callback = function()
       loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/bruvzz/oasishub/main/script"))()
   end,
})






local FETab = Window:CreateTab("FE", 4483362458)
 
local Section = FETab:CreateSection("Netless Bypass")

 local MainButton = FETab:CreateButton({
   Name = "Netless",
   Callback = function()
       loadstring(game:HttpGet(('https://pastebin.com/raw/Cu7bKQWN'),true))()
   end,
})
 

local Section = FETab:CreateSection("GUI/Hub")

local Button = FETab:CreateButton({
   Name = "Energize Animation GUI (R6)",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/RmD3qNp7",true))()
   end,
})
 

local Button = FETab:CreateButton({
   Name = "BTR Animation GUI R6",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/bVMjrXpC",true))()
   end,
})

local Button = FETab:CreateButton({
   Name = "Sushi Hub X",
   Callback = function()
      loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/sushi/main/X'),true))()
   end,
})


local Section = FETab:CreateSection("FE scripts")

local Button = FETab:CreateButton({
   Name = "Hat Universe",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/4B4fktPS", true))()
   end,
})
 




local Button = FETab:CreateButton({
   Name = "FE-Flip (Z,X,C)",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/xi23b40Y",true))()
   end,
})

local Button = FETab:CreateButton({
   Name = "Trash PP (Q)",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/khQeXj9q",true))()
   end,
})



 



local OthersTab = Window:CreateTab("VYZ", 4483362458)
 

 local Button = OthersTab:CreateButton({
    Name = "AutoReport",
    Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/fa899/Auto-Report/main/Auto%20Report%20Script%20(OP)'))()
    end,
 })

 local BestSection = GamesTab:CreateSection("XYZ")

local MainButton = GamesTab:CreateButton({
   Name = "Mukuro X",
   Callback = function()
      loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
   end,
})

local Button = GamesTab:CreateButton({
   Name = "Oasis X",
   Callback = function()
       loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/bruvzz/oasishub/main/script"))()
   end,
})

local MainButton = GamesTab:CreateButton({
   Name = "JNHH'S MVSD Blatant",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/RfRUnVk6"))()
   end,
})

 local FruitsSection = GamesTab:CreateSection("Blox Fruits")
 
 
 
 local MainButton = GamesTab:CreateButton({
   Name = "Mukuro",
   Callback = function()
      loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
   end,
})
 
 
local MainButton = GamesTab:CreateButton({
   Name = "Hoho",
   Callback = function()
      loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
   end,
})



local MainButton = GamesTab:CreateButton({
   Name = "ATR",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/ATR",true))()
   end,
})


local MainButton = GamesTab:CreateButton({
   Name = "StringX",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/StringV2/StringHub/main/BF.txt", true))()
   end,
})



local MainButton = GamesTab:CreateButton({
   Name = "Treasure Chest Steal",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/Cesare0328/my-scripts/main/fxss%20bf.lua"))()
   end,
})


local MVSDSection = GamesTab:CreateSection("Murderer Vs Sherrif Duels")

 

local MainButton = GamesTab:CreateButton({
   Name = "JNHH'S MVSD Blatant",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/RfRUnVk6"))()
   end,
})


local Button = GamesTab:CreateButton({
   Name = "Oasis Hub X",
   Callback = function()
       loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/bruvzz/oasishub/main/script"))()
   end,
})




local MainButton = GamesTab:CreateButton({
    Name = "Murderer Vs Sherrif AutoKill",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Kenniel123/Murderers-VS-Sheriffs-Duels-script/main/Murderers%20VS%20Sheriffs%20Duels%20script",true))();
    end,
 })


 local MainButton = GamesTab:CreateButton({
   Name = "Murderer Vs Sherrif Emptyiness Hub",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/EmptynessNoBlur"))()
   end,
})
