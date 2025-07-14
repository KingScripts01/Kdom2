loadstring("game:GetService(\"StarterGui\"):SetCore(\"SendNotification\",{\
    Title = \"this admin made by\";\
    Text = \"!KINGMODSCRACKED\";\
    Duration = 5;\
})\
local Player = game.Players.LocalPlayer\
\
Player.Chatted:connect(function(chat)\
    if chat:match(\".gun mod\") then\
        local list = require(game:GetService(\"ReplicatedStorage\").GunScripts.GunStats)\
        for i,v in pairs(list) do\
            v.Spread = 0\
            v.prepTime = 0.1\
            v.eqTime = 0.1\
            v.MaxShots = math.huge\
            v.ReloadSpeed = 0.1\
            v.BulletSpeed = 250\
            v.HipFireAccuracy = 0\
            v.ZoomAccuracy = 0\
        end\
        else\
            elseif chat:match(\".bank\") then\
            local o = game.Players.LocalPlayer.Character.HumanoidRootPart\
            local lol = CFrame.new(Vector3.new(1620.7681984911695, 1219.3499576089776, 1556.9338576405206), Vector3.new(1129.3499576089776, 1.449999988079071, 865.1280213003163))\
            o.CFrame = lol\
        end\
    end\
end)
