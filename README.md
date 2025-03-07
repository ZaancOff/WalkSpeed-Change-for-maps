# WalkSpeed-Change-for-maps
For roblox studio (idk)
____________________________________

```-- Получаем ссылку на игрока и его персонажа
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Устанавливаем желаемую скорость
local desiredWalkSpeed = 50 -- это значение можно изменить

-- Изменяем скорость персонажа
character:WaitForChild("Humanoid").WalkSpeed = desiredWalkSpeed

print("Скорость персонажа изменена на: " .. desiredWalkSpeed)```
