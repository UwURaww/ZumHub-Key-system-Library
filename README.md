# ZumHub Key System Library

---

<div align="center">
  <img src="https://github.com/user-attachments/assets/b78ff0d2-a0b2-4b65-82f8-34d371701708" alt="ZumHub Banner" width="100%" />
</div>

<p align="center">
  <b>Professional, Customizable Key System for Roblox GUIs</b><br>
  <i>Powered by <a href="https://junkie-development.de/">Junkie Development</a></i>
</p>

---

## ✨ Overview

ZumHub Key System Library offers a modern, highly customizable, and secure key-based authentication for Roblox GUIs. Simplify access control and user management in your scripts with easy configuration and seamless integration.

---

## ⚙️ Configuration

Easily adjust every aspect of your key system to match your branding and workflow.

```lua
-- Config Section
Config = {
    api = "_API_",
    service = "_Service_",
    provider = "_provider_",
    discordInvite = "kv5wr2Naj", -- Discord invite link
    title = "ZumHub Key System", -- GUI title
    keyFileName = "Zumhubkey.txt", -- Saved key filename
    scriptUrl = "https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Protected_6601639189420021.lua", -- Script to execute on success
    sounds = {
        uiOpen = "rbxassetid://6655851046",
        buttonClick = "rbxassetid://6655851046",
        success = "rbxassetid://6655851046",
        successDiscord = "rbxassetid://6655851046",
        error = "rbxassetid://6655851046",
        accessDenied = "rbxassetid://6655851046"
    },
    colors = {
        background = Color3.fromRGB(10, 10, 25),
        backgroundGradientFrom = Color3.fromRGB(10, 10, 30),
        backgroundGradientTo = Color3.fromRGB(5, 5, 15),
        title = Color3.fromRGB(0, 255, 200),
        inputField = Color3.fromRGB(20, 20, 40),
        inputFieldBorder = Color3.fromRGB(0, 200, 255),
        button = Color3.fromRGB(30, 30, 50),
        buttonHover = Color3.fromRGB(50, 50, 80),
        error = Color3.fromRGB(255, 80, 80),
        success = Color3.fromRGB(80, 255, 100),
        discord = Color3.fromRGB(160, 80, 255)
    }
}
```

---

## 🚀 Quick Start

Add the following to your script to instantly enable the ZumHub Key System:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Key%20system%20main.lua.txt",true))()
```

---

## 💡 Example Implementation

```lua
-- Config Section
Config = {
    api = "_API_",
    service = "_Service_",
    provider = "_provider_",
    discordInvite = "kv5wr2Naj", -- Discord invite link
    title = "ZumHub Key System", -- GUI title
    keyFileName = "Zumhubkey.txt", -- Saved key filename
    scriptUrl = "https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Protected_6601639189420021.lua", -- Script to execute on success
    sounds = {
        uiOpen = "rbxassetid://6655851046",
        buttonClick = "rbxassetid://6655851046",
        success = "rbxassetid://6655851046",
        successDiscord = "rbxassetid://6655851046",
        error = "rbxassetid://6655851046",
        accessDenied = "rbxassetid://6655851046"
    },
    colors = {
        background = Color3.fromRGB(10, 10, 25),
        backgroundGradientFrom = Color3.fromRGB(10, 10, 30),
        backgroundGradientTo = Color3.fromRGB(5, 5, 15),
        title = Color3.fromRGB(0, 255, 200),
        inputField = Color3.fromRGB(20, 20, 40),
        inputFieldBorder = Color3.fromRGB(0, 200, 255),
        button = Color3.fromRGB(30, 30, 50),
        buttonHover = Color3.fromRGB(50, 50, 80),
        error = Color3.fromRGB(255, 80, 80),
        success = Color3.fromRGB(80, 255, 100),
        discord = Color3.fromRGB(160, 80, 255)
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/UwURaww/-ZumHub-Script-/refs/heads/main/Key%20system%20main.lua.txt",true))()
```

---

## 🛠️ Setup Guide

### 1. Register & Configure on Junkie Development

1. Go to <a href="https://junkie-development.de/" target="_blank"><b>junkie-development.de</b></a>  
   <div align="center"><img src="https://github.com/user-attachments/assets/9f447da6-c9c8-4587-8399-e70e8ff523b8" width="60%"/></div>
2. Click <b>Start Now</b> and log in.  
   <div align="center"><img src="https://github.com/user-attachments/assets/6822770f-f92f-4075-a1b5-6840155b196c" width="60%"/></div>
3. Create a <b>Service</b>.  
   <div align="center"><img src="https://github.com/user-attachments/assets/28069675-eb29-4ec5-9891-15079f356954" width="60%"/></div>
   <div align="center"><img src="https://github.com/user-attachments/assets/0b200502-e80c-43f4-a9d5-c59326a79c95" width="60%"/></div>
4. Add an <b>Integration</b>.  
   <div align="center"><img src="https://github.com/user-attachments/assets/a69158df-4f7b-40e6-a6c1-a0bb6db296f6" width="60%"/></div>
5. Create <b>Providers</b>.  
   <div align="center"><img src="https://github.com/user-attachments/assets/2f1323d2-b25a-4a61-8ea5-a236c73a1b33" width="60%"/></div>
   <div align="center"><img src="https://github.com/user-attachments/assets/03e21629-2b20-4ac5-b00c-a4880cf41c00" width="60%"/></div>
6. Generate your <b>API Keys</b>.  
   <div align="center"><img src="https://github.com/user-attachments/assets/9e2b0915-b3da-4f20-a687-95b80c88d3e2" width="60%"/></div>
   <div align="center"><img src="https://github.com/user-attachments/assets/02fc9394-de9d-4f37-a1b0-a89a4f129c4e" width="60%"/></div>

---

### 2. Finalize Your Config

Copy your API key, service, and provider details into the `Config` section above.

---

## 🎉 You're Done!

Your professional key system is ready to protect your Roblox scripts.

---

> **Crafted with ❤️ by [Jardin-ZumHub Yt](https://youtube.com/@Jardin-ZumHub)**
