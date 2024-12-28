-- carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "henryhub " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
    })
    
    
    local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
 }   
 
 Tabs.Main:AddParagraph({ Title = "henry", Content = "This is a paragraph.\nSecond line!" })
 
 --botōes
Tabs.Main:AddButton({ Title = "autofarm", Callback = function()loadstring(game:HttpGet("https://github.com/WarzMvp/blox-fruits-script.git"))()
end }) 
 
 Window:SelectTab(1)
Fluent:Notify({ Title = "Fluent", Content = "The script has been loaded." })
