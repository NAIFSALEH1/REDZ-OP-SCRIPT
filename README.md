game.Players.PlayerAdded:Connect(function(player)
    wait(1) -- espera un segundo para que el jugador se cargue
    player:Kick("HAHA! LO LOGRASTE")
end)
