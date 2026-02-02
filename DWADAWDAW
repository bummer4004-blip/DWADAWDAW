local url = "https://pastefy.app/6AK5Kf3F/raw"
local success, result = pcall(game.HttpGet, game, url, true)

if success then
    if result and #result > 0 then
        print("Успех! Код получен, длина: " .. #result .. " символов")
        -- loadstring(result)()  -- раскомменти если хочешь запустить
    else
        print("HttpGet вернул пустую строку или nil")
    end
else
    warn("HttpGet крашнулся: " .. tostring(result))
end
