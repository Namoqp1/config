_G.autohit = true


while _G.autohit do wait(0)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Lives.Sans0.HumanoidRootPart.CFrame * CFrame.new(0, 0, 1)
game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
game:GetService("VirtualInputManager"):SendKeyEvent(true,122,false,game.Players.LocalPlayer.Character.HumanoidRootPart)
game:GetService("VirtualInputManager"):SendKeyEvent(true,120,false,game.Players.LocalPlayer.Character.HumanoidRootPart)
game:GetService("VirtualInputManager"):SendKeyEvent(true,99,false,game.Players.LocalPlayer.Character.HumanoidRootPart)
game:GetService("VirtualInputManager"):SendKeyEvent(true,118,false,game.Players.LocalPlayer.Character.HumanoidRootPart)
end
