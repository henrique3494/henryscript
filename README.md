local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "henryhub v2",
    Size = UDim2.fromOffset(400, 300),
    Theme = "dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
 }   
 
 Tabs.Main:AddParagraph({ Title = "bloxfruits", Content = "This is a paragraph.\nSecond line!" })
 
  --botōes
Tabs.Main:AddButton({ Title = "autofarm", Callback = function()loadstring(game:HttpGet("https://github.com/WarzMvp/blox-fruits-script.git"))()
end }) 

Window:SelectTab(1)
Fluent:Notify({ Title = "Fluent", Content = "The script has been loaded." })
