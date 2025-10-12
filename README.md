# ZumHub-Key-system-Library

---

<div align="center">
  <img src="https://github.com/user-attachments/assets/b78ff0d2-a0b2-4b65-82f8-34d371701708" alt="ZumHub Banner" width="100%" />
</div>

> **Note**  
> This Key system uses [Junkie development](https://junkie-development.de/)

---

## ⚙️ Config

```lua
-- Config Section
Config = {
    api = "__Yourapi__",
    service = "__Youtservice__",
    provider = "__YourProvider__",
    discordInvite = "kv5wr2Naj", -- Change this to update the Discord invite link
    title = "ZumHub Key System", -- Change this to update the GUI title
    keyFileName = "Zumhubkey.txt", -- Change this to update the saved key filename
    scriptUrl = "https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Protected_6601639189420021.lua", -- Change this to update the script to execute
    intro = {
        enabled = true, -- Set to false to disable the intro
        text = "Welcome to ZumHub", -- Change this to customize the intro text
        duration = 2, -- Duration of the intro animation in seconds
        textColor = Color3.fromRGB(0, 255, 200), -- Color of the intro text
        backgroundColor = Color3.fromRGB(10, 10, 25), -- Background color of the intro
        soundId = "rbxassetid://6655851046", -- Sound to play during intro (change to custom sound ID)
        font = Enum.Font.SciFi, -- Font for the intro text (e.g., Enum.Font.SciFi, Enum.Font.SourceSans, etc.)
        textSize = 24, -- Size of the intro text
        iconId = "rbxassetid://0", -- Icon asset ID for the intro (change to a valid Roblox image asset ID, e.g., "rbxassetid://1234567890")
        iconSize = UDim2.new(0, 100, 0, 100), -- Size of the icon (width, height in pixels)
        enableBlur = true -- Set to true to enable blur effect on background, false to disable
    }
}
-- End Config Section
```

---

## 🚀 Main Script (**Required**)

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Key%20system%20main.lua.txt",true))()
```

---

# 🌟 Implementation Example

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

loadstring(game:HttpGet("https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Key%20system%20main.lua.txt",true))()
```

---

# 🛠️ Setup Guide

## 🔑 Login Steps

1. Go to [junkie-development.de](https://junkie-development.de).
    <div align="center"><img src="https://github.com/user-attachments/assets/9f447da6-c9c8-4587-8399-e70e8ff523b8" width="60%"/></div>
2. Click **Start Now** and **Login**.<br>
    <div align="center"><img src="https://github.com/user-attachments/assets/6822770f-f92f-4075-a1b5-6840155b196c" width="60%"/></div>
3. Create a **Service**.<br>
    <div align="center"><img src="https://github.com/user-attachments/assets/28069675-eb29-4ec5-9891-15079f356954" width="60%"/></div>
    <div align="center"><img src="https://github.com/user-attachments/assets/0b200502-e80c-43f4-a9d5-c59326a79c95" width="60%"/></div>
4. Add **Integration**.<br>
    <div align="center"><img src="https://github.com/user-attachments/assets/a69158df-4f7b-40e6-a6c1-a0bb6db296f6" width="60%"/></div>
5. Create **Providers**.<br>
    <div align="center"><img src="https://github.com/user-attachments/assets/2f1323d2-b25a-4a61-8ea5-a236c73a1b33" width="60%"/></div>
    <div align="center"><img src="https://github.com/user-attachments/assets/03e21629-2b20-4ac5-b00c-a4880cf41c00" width="60%"/></div>
6. Create **API Keys**.<br>
    <div align="center"><img src="https://github.com/user-attachments/assets/9e2b0915-b3da-4f20-a687-95b80c88d3e2" width="60%"/></div>
    <div align="center"><img src="https://github.com/user-attachments/assets/02fc9394-de9d-4f37-a1b0-a89a4f129c4e" width="60%"/></div>

---

## 🎉 Finish

**VOILA, YOU'RE DONE!**  
Just insert your API key, service, and provider names into your config.

> **Note**  
> # By Jardin-ZumHub Yt

---
