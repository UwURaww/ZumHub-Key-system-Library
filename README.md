# ZumHub-Key-system-Library
Key system using https://junkie-development.de


 ## Config
```lua
-- Config Fields
title = "ZumHub Key System"
description = "Enter your key to access the script."
discordInvite = "kv5wr2Naj"
FileName = "Zumhubkey.txt"
KeySystemData = {
    Name = "ZumHub KeySystem",
    Colors = {
        Background = Color3.fromRGB(10, 10, 25),
        BackgroundGradientFrom = Color3.fromRGB(10, 10, 30),
        BackgroundGradientTo = Color3.fromRGB(5, 5, 15),
        Title = Color3.fromRGB(0, 255, 200),
        InputField = Color3.fromRGB(20, 20, 40),
        InputFieldBorder = Color3.fromRGB(0, 200, 255),
        Button = Color3.fromRGB(30, 30, 50),
        ButtonHover = Color3.fromRGB(50, 50, 80),
        Error = Color3.fromRGB(255, 80, 80),
        Success = Color3.fromRGB(80, 255, 100),
        Discord = Color3.fromRGB(160, 80, 255)
    },
    Service = "ZumHubKey",
    SilentMode = false,
    WebsiteURL = "https://yourwebsite.com/"
}

-- Default Config
local Config = {
    api = "__YourAPI__",
    service = "__YOUR SERVICE__",
    provider = "__YOUR PROVIDER__",
    loadstringUrl = "https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Protected_6601639189420021.lua" --enter your script 
}

-- Allow manual override before script runs (e.g., in executor)
-- Example: getgenv().CustomConfig = {api = "newApi", service = "newService", provider = "newProvider", loadstringUrl = "newUrl"}
if getgenv().CustomConfig then
    local function updateConfig(newConfig)
        if newConfig then
            Config.api = newConfig.api or Config.api
            Config.service = newConfig.service or Config.service
            Config.provider = newConfig.provider or Config.provider
            Config.loadstringUrl = newConfig.loadstringUrl or Config.loadstringUrl
        end
    end
    updateConfig(getgenv().CustomConfig)
end
```


## Main Script (REQUIRED)
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Key%20system%20main.lua.txt",true))()
```
