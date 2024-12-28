-- carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "henryhub " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
    ))
    
    
    local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
 }   
 
 Tabs.Main:AddParagraph({ Title = "henry", Content = "This is a paragraph.\nSecond line!" })
 
 --botōes
Tabs.Main:AddButton({ Title = "autofarm", Callback = function()https://github.com/Blox-Fruits-Auto-Far/Blox-Fruits-Auto-Far.git
end }) 
 
