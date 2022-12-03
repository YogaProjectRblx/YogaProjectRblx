local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))() local Window = Library.CreateLib("YogaExploits Zerpent HUB", "Synapse") local Tab = Window:NewTab("Robux For Cash Shop") local Section = Tab:NewSection("Robux Cash Shop") Section:NewButton("F", "50K", function() local args = { [1] = "F" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Harambe", "1M", function() local args = { [1] = "Box Toy Harambe" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Sanic", "50K", function() local args = { [1] = "Box Toy Sanic" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("SandMan", "50K", function() local args = { [1] = "Box Toy SandMan" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("A", "20K", function() local args = { [1] = "A" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Lem", "60K", function() local args = { [1] = "Box Toy Lem" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("XOX Controller", "50K", function() local args = { [1] = "XOX Controller" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Dart", "6M", function() local args = { [1] = "Dart" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Retro Bike", "50K", function() local args = { [1] = "Retro Bike" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Demogorgan", "2M ", function() local args = { [1] = "Demogorgan" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Demogorgan Kawaii", "2M", function() local args = { [1] = "Demogorgan Kawaii" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Talky", "250", function() local args = { [1] = "Walky Talky" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Buy All The Alphabets", "Buy All Alphabets", function() local args = { [1] = "C" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) wait(1) local args = { [1] = "F" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) wait(1) local args = { [1] = "A" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) local args = { [1] = "B" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) wait(1) local args = { [1] = "D" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) wait(1) local args = { [1] = "E" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) wait(1) local args = { [1] = "G" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Green Ooze", "50", function() local args = { [1] = "Green Ooze" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Box", "1K", function() local args = { [1] = "Box Toy Box Toy" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Egg", "500", function() local args = { [1] = "Box Toy Egg" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Air(Not Nothing)", "250", function() local args = { [1] = "Box Toy Air"} game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Noob", "2.5K", function() local args = { [1] = "Box Toy Noob" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) Section:NewButton("Box Toy Houss(WORKING NOW)", "Buys The New Unpatched Box House.", function() local args = { [1] = "Box Toy  House" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end) local Section = Tab:NewSection("Auto Buy") Section:NewToggle("Auto Buy F", "Auto F", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "F" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Harambe", "Auto Harambe", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Harambe" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Sanic", "Auto Sanic", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Sanic" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy SandMan", "Auto SandMan", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy SandMan" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy A", "Auto A", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "A" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Lem", "Auto Lem", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Lem" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Controller", "Auto Controller", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "XOX Controller" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Dart", "Auto Dart", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Dart" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Retro Bike", "Auto Retro Bike", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Retro Bike" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Air", "Auto Air", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Air" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Noob", "Auto Noob", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Noob" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Dart", "Auto Dart", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Dart" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Talky", "Auto Talky", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Walky Talky" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Air", "Auto Air", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Air" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Box", "Auto Box", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy Box Toy" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end) Section:NewToggle("Auto Buy Green Ooze", "Auto Green Ooze", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Green Ooze" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end)  Section:NewToggle("Auto Buy Box Toy House", "Auto House", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Box Toy  House" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end)  Section:NewToggle("Auto Silver PlayButton", "Auto PlayButton", function(state) if state then _G.on = true while _G.on do wait() local args = { [1] = "Silver" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end else _G.on = false end end)  local Section = Tab:NewSection("Normal Items") Section:NewButton("Banana", "999B", function() local args = { [1] = "The Banana" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Pop It Rainbow", "600M", function() local args = { [1] = "Pop It Rainbow!" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Angel Eye", "999M", function() local args = { [1] = "Angel Eye" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Lolly Rainbow", "300M", function() local args = { [1] = "Lolly Rainbow" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Amogus Rainbow", "300M", function() local args = { [1] = "Amogus Rainbow" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Crystal Rainbow", "100M", function() local args = { [1] = "Crystal Rainbow" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Slippy Rainbow", "75M", function() local args = { [1] = "Slippy Rainbow" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Gummy Rainbow", "20M", function() local args = { [1] = "Gummy Rainbow" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Gem Rainbow", "17M", function() local args = { [1] = "Gem Rainbow" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  local Section = Tab:NewSection("Rainbow Friends Set")  Section:NewButton("Friend Pink", "1K", function() local args = { [1] = "Friend Pink" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Friend Orange", "2.5k", function() local args = { [1] = "Friend Orange" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Friend Green", "50", function() local args = { [1] = "Friend Green" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Friend Purple", "500", function() local args = { [1] = "Friend Purple" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Coming Soon (Friend Blue)", "100 Robux", function() local args = { [1] = "Friend Blue" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  local Section = Tab:NewSection("Doors Set")  Section:NewButton("Eie", "20", function() local args = { [1] = "Eie" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Meat", "1K", function() local args = { [1] = "Meat" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Gl1tch", "5K", function() local args = { [1] = "Gl1tch" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Eyye", "50K", function() local args = { [1] = "Eyye" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Glitch Particle", "50K", function() local args = { [1] = "Glitch" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Screeech", "100K", function() local args = { [1] = "Screeech" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  local Section = Tab:NewSection("UI Toggler")  Section:NewKeybind("Toggle UI", "Toggles the UI.", Enum.KeyCode.F, function()

	Library:ToggleUI()end)  Section:NewLabel("Alphabets!")  Section:NewButton("A", "1K", function() local args = { [1] = "A" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("B", "100", function() local args = { [1] = "B" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("C", "20", function() local args = { [1] = "C" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("D", "50", function() local args = { [1] = "D" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  local Section = Tab:NewSection("Fake Drop🤡")  Section:NewButton("Fake Drop", "OP Fake Drop ", function()

    local plr = game.Players.LocalPlayer

local chr = plr.Character

chr.RightHand:Destroy()

end)  Section:NewButton("Reset", "Resets Fake Drop.", function()

local plr = game.Players.LocalPlayer

local chr = plr.Character

chr.Head:Destroy()

end)  local Section = Tab:NewSection("Code Items!")  Section:NewButton("Inxta", "Buys The Inxta Code Item.", function() local args = { [1] = "Inxta" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Tweet", "Buys The Tweet Code Item.", function() local args = { [1] = "Tweet" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  Section:NewButton("Tix Tox", "Buys The Tix Tox Code Item.", function() local args = { [1] = "Tix Tox" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  local Section = Tab:NewSection("Silver Playbutton Shop")  Section:NewButton("Silver Playbutton", "Buys The Silver PlayButton.", function() local args = { [1] = "Silver" } game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args)) end)  local Section = Tab:NewSection("Teleports")  Section:NewButton("Golden Place", "Teleports You To The Golden Place.", function()

    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(215.85202026367188, 25.547666549682617, 11380.29296875)

end)  local Section = Tab:NewSection("XRAY")  Section:NewButton("Free XRAY", "Turns On XRAY For Free", function()

    game.Players.localPlayer.XRay.Value = true

end)  local Section = Tab:NewSection("⚠️Warning⚠️")  local Section = Tab:NewSection("This Script No Have Protection")  local Section = Tab:NewSection("Change To Get Banned Warning")  local Section = Tab:NewSection("Credits")  local Section = Tab:NewSection("Akari,Balli And B)")  local Section = Tab:NewSection("YoProject???")  local Section = Tab:NewSection("Beta Testers!")  local Section = Tab:NewSection("Thanks To Balligusapo YT!")  local Section = Tab:NewSection("Kavo UI😎")  local Section = Tab:NewSection("Updated By YogaExploits")

--Tabs
local Tab2 = Window:NewTab("Misc")


--Sections inside tabs
local Tab2Section = Tab2:NewSection("Scripts")


--Buttons
Tab2Section:NewButton("Infinite Yield", "Executes Infiniteyield", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()

end)
Tab2Section:NewButton("giant", "makes you giant (r15)", function()
    --Script made by failedmite57926
local LocalPlayer = game:GetService("Players").LocalPlayer
local Character = LocalPlayer.Character
local Humanoid = Character:FindFirstChildOfClass("Humanoid")
function rm()
	for i,v in pairs(Character:GetDescendants()) do
		if v:IsA("BasePart") then
			if v.Name == "Handle" or v.Name == "Head" then
				if Character.Head:FindFirstChild("OriginalSize") then
					Character.Head.OriginalSize:Destroy()
				end
			else
				for i,cav in pairs(v:GetDescendants()) do
					if cav:IsA("Attachment") then
						if cav:FindFirstChild("OriginalPosition") then
							cav.OriginalPosition:Destroy()  
						end
					end
				end
				v:FindFirstChild("OriginalSize"):Destroy()
				if v:FindFirstChild("AvatarPartScaleType") then
					v:FindFirstChild("AvatarPartScaleType"):Destroy()
				end
			end
		end
	end
end
rm()
wait(0.5)
Humanoid:FindFirstChild("BodyProportionScale"):Destroy()
wait(1)
rm()
wait(0.5)
Humanoid:FindFirstChild("BodyHeightScale"):Destroy()
wait(1)
rm()
wait(0.5)
Humanoid:FindFirstChild("BodyWidthScale"):Destroy()
wait(1)
rm()
wait(0.5)
Humanoid:FindFirstChild("BodyDepthScale"):Destroy()
wait(1)
rm()
wait(0.5)
Humanoid:FindFirstChild("HeadScale"):Destroy()
wait(1)
end)
Tab2Section:NewButton("Trade Value", "Gives you trade value", function()
    game.Players.localPlayer.XRay.Value = true
end)
Tab2Section:NewButton("fake drop gui", "Executes fake drop gui", function()
    loadstring(game:HttpGet("https://gist.githubusercontent.com/domdaobfuscater/09214a11b8a30bab47ceff281116195f/raw/40356a0ff4542a51283ab5de0a642233a6ceb6f9/gistfile1.txt"))()
end)
Tab2Section:NewButton("rejoin server", "rejoins the server", function()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").LocalPlayer)
end)
Tab2Section:NewButton("Deleted Item [ F ]", "Deleted Other Item Press F", function()

    --[[
    script by Stan#8292
]]
getgenv().bind = "F" --keybind to delete popits near you
getgenv().invis = false --turns you invis so people cant see you deleting their stuff (resetting will uninvis you)
getgenv().on = true --setting this to false will stop the script
getgenv().IgnoredList = { --ignored people (script won't delete popits from these people)
    "Person1",
    "Person2",
    "Person3"
}

local domain = "paste.ee"
loadstring(game:HttpGet("https://"..domain.."/r/WFYpr/0"))()
end)
Tab2Section:NewButton("Keyboard Script", "Keyboard Script", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()

end)
