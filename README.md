# Pira-script
Petsimulator99
getgenv().Config = {
    ["Farming"] = {
        ["AreaToFarm"] = 8,
        ["StartAtBottom"] = true,
        ["AutoCraft"] = false, -- Autocraft Onyx Gems // After max cheaper upgrade is bought
    },
    ["Pickaxe"] = {
        ["AutoEnchant"] = false, -- Enchants ur best Pickaxe
        ["GetAllEnchants"] = false,
        ["PickaxeEnchants"] = {
            ["Fortune"] = 3, -- This will stop at Fortune 3, 4, 5
            ["Diamond Farmer"] = 5, -- This will stop at Diamond Farmer 5
        },
    }
}
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/d0b7e7eced327afcbf466e8c5ad296f8.lua"))()

task.await(5)
loadstring(game:HttpGet('https://raw.githubusercontent.com/tobi437a/Scripts/refs/heads/main/0cc8fc259add576d1f9cf2f9.lua'))()
