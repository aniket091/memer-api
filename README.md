# Memer API
<p align="center"><a href="https://memer-api.js.org/"><img align="center" style="width:0.5px" src="https://cdn.discordapp.com/attachments/801132434283954199/881571725106618428/memer_api.png"/></a></p><br/>
<p align="center">
   <img alt="npm" src="https://img.shields.io/npm/dt/memer-api">
   <a href="https://discord.gg/invite/emD44ZJaSA"><img src="https://img.shields.io/discord/664505860327997461?color=5865F2&label=Meme%20Development" alt="Discord Server"></a>
   <a href="https://www.buymeacoffee.com/memerapi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="28.7" width="121.8"></a>

</p>
      
> **Memer API is a powerful module that allows you to manipulate images very easily :)**
> 

## **Installation** 
```
npm install memer-api
```
```js
const Meme = require("memer-api");
const memer = new Meme('Your Cool API Token');  // From Memer API Server :)
memer.<Method>(<Options>); //returns -> Promise -> <Buffer>
```

## LINKS

- 📃 Guide/Docs: [Documentation](https://memer-api.js.org/)
- 💬 Discord: [Server](https://discord.com/invite/emD44ZJaSA)


## Features

- Super simple and easy to use.
- More than 50+ methods. Yay 🎉
- Easy to Implement.
- Great support and flexible.


## Examples

```js
const Meme = require("memer-api")
const Discord = require("discord.js")
cosnt memer = new Meme('Your Cool API Token'); // From Memer API Server :)

const avatar = "https://imgur.com/I5DmdNR.png"; // Only static images are supported :)
const text = "Memer API is awesome!"

memer.youtube(avatar, 'Memer Api', text).then(image => {
    // This gives you a 'Buffer', for Discord to create an attachment
    
    var attachment = new Discord.MessageAttachment(image, "youtube.png");
    <channel>.send(attachment)
})
```

## Hosting | Bittmax.de
> **BITTMAX Quality is their solution. Bittmax is our first and probably most important sponsor!**

### What they are offering:
> **Quality LXC & KVM (Root) Server Minecraft Hosting, as well as BungeeCord Network Hosting support Cheap and fast Domains WEBHOSTING DISCORD, TEAMSPEAK, Setups / Music Bots GAME > SERVER, Rust, Gary's Mod and so much more!**

Discord : [Server!](https://discord.gg/NTnPuSaZVg) 

Website: [Link!](https://bittmax.de/)

## Credits
Image Gen: [Link!](https://github.com/DankMemer/imgen)

Wrapper: [Based from Snowflake's Api Wrapper](https://github.com/DevSnowflake/dankmemer.js#readme)

Made by: [@Yash094](https://github.com/Yash094)


## Preview

![preview](https://cdn.discordapp.com/attachments/806750853947719760/843579019823546368/memer-api_preview.png)

