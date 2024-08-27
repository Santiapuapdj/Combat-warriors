# Combat-warriors
-- Assuming you have a function named 'isEnemyAboutToAttack' to predict an enemy's attack -- and a function named 'parry' to execute the parry action  local function autoParry()     if isEnemyAboutToAttack() then         parry()     end end  -- Assuming you can access the game's RunService game:GetService("RunService").Heartbeat:Connect(autoParry)
