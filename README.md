***The script is detected rn but it still works and you wont get banned. It only kicks you every once in a while***

If you want to modify the script and add your own teleports just open the .lua file in a code editor like serris code editor and copypaste one of the teleports or use this format and paste it right below the other ones with a one line gap:
```
-- Name of TP
TeleportTab:CreateButton({
    Name = "Name of TP",
    Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new("X coord here", "Y coord here", "Z coord here", -0.174461573, 0.59867698, -3.93326582e-06, 0.960067034, 0.279769868, -0.623579144, 0.218710497, -0.75054276)
    end
})
```
All you have to do is rename the copypasted TP and replace the "_ coord here" section with whatever the coords are on the GPS. (Don't forget to remove the "" marks).

If you want to use Auto Farm you are going to have to modify this line of code(It appears twice in the code so you have to change it in both lines for it to work):
```
local rod = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Arctic Rod")
```
