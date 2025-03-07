# WalkSpeed-Change-for-maps
For roblox studio (idk)
____________________________________

```
print("CREATED BY ZA_ANC")
-- Get player and character
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Make speed
local desiredWalkSpeed = 50 -- You can change this

-- Changes speed character
character:WaitForChild("Humanoid").WalkSpeed = desiredWalkSpeed

print("Player speed changed on: " .. desiredWalkSpeed)
```
