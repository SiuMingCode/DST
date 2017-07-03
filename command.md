# Command

Action|Command
:-:|:-:
復活自己|c_godmode(1)
復活他人|AllPlayers[`number`]:PushEvent('respawnfromghost')
開啟全圖|minimap = TheSim:FindFirstEntityWithTag("mini­map")<br>TheWorld.minimap.MiniMap:ShowArea (0,0,0,10000)
Teleport|c_goto(AllPlayers[`number`])