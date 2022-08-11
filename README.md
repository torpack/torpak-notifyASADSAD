# torpak-notify
Standalone Notfiy System. rework of qb-notify 

How Can I Use (Nasıl Kullanılır)
Like This:

On Client:
```lua
exports['torpak-notify']:SendAlert('This Is Client Message', 'info')
```

##With Caption (Alt Metin İle)
```lua
exports['torpak-notify']:SendAlert({text = 'This Is Client Message', caption = 'With Caption'}, 'info')
```

### On Server:
## Send to everyone (Bütün Oyunculara Yolla)
```lua
TriggerClientEvent('torpak:notify', -1, 'This is a test', 'info')
```
With Caption(Alt Metin İle)
```lua
TriggerClientEvent('torpak:notify', -1, {text = 'This is a test notification', caption = 'With caption'}, 'info')
```
## Send to source(Source'a Yolla)
```lua
TriggerClientEvent('torpak:notify', source, 'This is a test', 'info')
```
With Caption(Alt Metin İle)
```lua
TriggerClientEvent('torpak:notify', source, {text = 'This is a test', caption = 'With caption'}, 'info')
```

## Previews
Info \
![Info](https://cdn.discordapp.com/attachments/708302355803799602/1007379630489075782/unknown.png) \
With Caption \
![Info](https://cdn.discordapp.com/attachments/708302355803799602/1007379663707971714/unknown.png)


Error \
![Error](https://cdn.discordapp.com/attachments/708302355803799602/1007379604736069763/unknown.png) 

Success \
![Success](https://cdn.discordapp.com/attachments/708302355803799602/1007379576126709800/unknown.png)  

With No Proggress \
![Warn](https://cdn.discordapp.com/attachments/708302355803799602/1007379987604705320/unknown.png)  
