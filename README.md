# luabasic

Une Documentation Personnalisée pour apprendre le Lua!

# 1. Player

Pour avoir accès au Player vous devez tout simplement chargé le modules suivant :

```bash
local Players = game:GetService("Players")
```
Ensuite pour avoir accès au LocalPlayer ainsi que le Character vous devrez les chargé comme ceci : 

```bash
local Player = Players.LocalPlayer
et pour le character
local character = Player.Character or Player.CharacterAdded:Wait()
```



