# luabasic

Une Documentation Personnalisée pour apprendre le Lua!

# 1. Player

Pour avoir accès au Player vous devez tout simplement chargé le modules suivant :

```bash
local Players = game:GetService("Players")
```
Ensuite pour avoir accès au LocalPlayer ainsi qu’au Character, vous devrez les charger comme ceci :

> [!TIP]
> Le `LocalPlayer` représente le joueur local sur le client.

```bash
local Player = Players.LocalPlayer
et pour le character
local character = Player.Character or Player.CharacterAdded:Wait()
```

> [!WARNING]
> `Les codes lua sont sensibles a la case!!`


