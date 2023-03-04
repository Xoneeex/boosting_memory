    local success = exports['boosting_memory']:StartBoostingMemory()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end