local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window  = Library.CreateLib("Made by: RedPogii aka jerfie22", "DarkTheme")
local Tab     = Window:NewTab("Main Scripts")
local Section = Tab:NewSection("Buy NFT Using (CASH)")
Section:NewButton("Buy Haramble", "Buy Ben", function()
    local args = {
        [1] = "Box Toy Harambe"
    }
    end)
    end
end
end)
end)

Section:NewButton("Buy F", "Buy Ben", function()

local args = {
    [1] = "F"
}

game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
