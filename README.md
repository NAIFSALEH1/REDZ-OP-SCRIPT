local Players = game:GetService("Players")

-- Function to kick a specific player
local function kickPlayer(player)
    if player and player.Character then
        -- Send a message to the player before kicking (optional)
        player:Kick("BITCH!")
    end
end

-- Example: Kick a player by name
local targetPlayerName = "PlayerNameHere" -- replace with the target player's username

local targetPlayer = Players:FindFirstChild(targetPlayerName)
if targetPlayer then
    kickPlayer(targetPlayer)
end

-- Alternatively, to kick all players (be cautious with this)
-- for _, player in pairs(Players:GetPlayers()) do
--     kickPlayer(player)
-- end
