_G.Autofarm = true
while _G.Autofarm do wait()
game:GetService("Players").LocalPlayer .ninjaEvent:FireServer("swingKatana")
wait(.1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71.1857986, 16.5895195, -46.5102806, -0.766061664, 0, -0.642767608, 0, 1, 0, 0.642767608, 0, -0.766061664)
end
_G.AutoBuy = true
while _G.AutoBuy do wait()
local args = {
   [1] = "buyAllSwords",
   [2] = "Ground"
}

game:GetService("Players").LocalPlayer.ninjaEvent:FireServer(unpack(args))
end
