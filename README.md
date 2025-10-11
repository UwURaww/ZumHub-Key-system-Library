# ZumHub-Key-system-Library
This code usng [Jukie]
(https://junkie-development.de/)


https://github.com/user-attachments/assets/1ef044fc-9f30-41e5-888a-720f93479a56


Key system using junkie development


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



# implementation
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






# Seting up
## Login
1.go to junkie-development.de.  
![1000443357](https://github.com/user-attachments/assets/9f447da6-c9c8-4587-8399-e70e8ff523b8)
2.Click Start Now and Login.  
![1000443359](https://github.com/user-attachments/assets/6822770f-f92f-4075-a1b5-6840155b196c)
3.Create service 
![1000443360](https://github.com/user-attachments/assets/28069675-eb29-4ec5-9891-15079f356954)

![1000443361](https://github.com/user-attachments/assets/0b200502-e80c-43f4-a9d5-c59326a79c95)
4.Add integration 
![1000443362](https://github.com/user-attachments/assets/a69158df-4f7b-40e6-a6c1-a0bb6db296f6)
5.Create providers
![1000443364](https://github.com/user-attachments/assets/2f1323d2-b25a-4a61-8ea5-a236c73a1b33)
![1000443370](https://github.com/user-attachments/assets/03e21629-2b20-4ac5-b00c-a4880cf41c00)
6.Create API Keys
![1000443370](https://github.com/user-attachments/assets/004b2e2b-cfbb-450d-8a3c-b1bb5047f5e0)
![1000443367](https://github.com/user-attachments/assets/02fc9394-de9d-4f37-a1b0-a89a4f129c4e)

## Finnish 
VOILA YOU'RE DONE 
you just need to insert you api key and insert
your service and providers name

# By Jardin-ZumHub Yt
