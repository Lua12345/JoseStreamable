local Rayfield = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Rayfield/main/source'))()


local Window = Rayfield:CreateWindow({
   Name = "Jose Streamable",
   LoadingTitle = "Jose Streamable",
   LoadingSubtitle = "by Jose | creds to Rayfield",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Josh Streamable"
   },
   Discord = {
      Enabled = false,
      Invite = "ABCD", -- The Discord invite code, do not include discord.gg/
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Jose streamable",
      Subtitle = "Key System",
      Note = "Jose streamable",
      FileName = "Josh",
      SaveKey = true,
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = "jose"
   }
})

local Tab = Window:CreateTab("Jose Streamable", 4483362458) -- Title, Image

local Section = Tab:CreateSection("Op Streamable")

local Button = Tab:CreateButton({
    Name = "Jose Main",
    Callback = function()
        local NotifyLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/vKhonshu/intro/main/ui"))()
        NotifyLib.prompt('Dm .lua#0001 For resolver for it', 'Loading..', 2)
        ---                              __________                       
        ----________        ____         |_________|||||||||||||
        ----| |_____|      //  \\        ||      ||    ||||  //            \\
        ----| |           //    \\       ||______||    |||| //              \\
        ----| |_____     //______\\      ||______||    ||||//                \\
        ----| |_____|   //________\\     ||     \\     ||||\\       //\\      \\  
        ----| |        //          \\    ||      \\    |||| \\     //  \\     //
        ----| |_____  //            \\   ||       \\   ||||  \\   //    \\   // 
        ----| |_____|//              \\  ||        \\  ||||   \\_//      \\_//
        ---____________________________________________________________________
        ----  ____
        ---  |____|  
            ---  ||
             --- ||  
              ---||
             ---//
        ----___//
        ----__//
        ---||
        ---||
        ---  
        ---O  
        ---      _       _
        ---    // \\   //\\      
        ---   //   \\_//  \\    
        ---   \\          //
        ---    \\        //
        ---     \\      //
        ---      \\    //
        ---       \\  //
        ---        \\//
        
        
        ---source code created by .lua 
        print("jose")
        print("Timer : 0")
        print("loaded")
        wait(4)
        local NotifyLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/vKhonshu/intro/main/ui"))()
        NotifyLib.prompt('jose Silent - Fov is 20 or higher', 'Loading..', 5)
        NotifyLib.prompt('jose Silent - shoot above head if needed', 'Loading..', 5)
        NotifyLib.prompt('jose Silent - Leaked By jose', 'Loading..', 5)
        loadstring(game:HttpGet("https://pastebin.com/raw/M3nt5Dad"))() 
    end,
 })

 local Button = Tab:CreateButton({
    Name = "camlock",
    Callback = function()
        getgenv().RecurringPoint = "UpperTorso"
        getgenv().Hitbox = "UpperTorso"
        getgenv().Keybind = "q"
        getgenv().AimbotStrengthAmount = .07422
        getgenv().PredictionAmount = 16
        getgenv().Radius = 25
        getgenv().UsePrediction = true
        getgenv().AimbotStrength = true
        getgenv().FirstPerson = true
        getgenv().ThirdPerson = true
        getgenv().TeamCheck = false
        getgenv().Enabled = true
        
        
        -- // main script use with silent aim / / -- 
        
        loadstring(game:HttpGet("https://raw.githubusercontent.com/tenaaki/GenericAimbot/main/v1.0.0"))()
    end,
 })
