const Aoijs = require("aoi.js")


const bot = new Aoijs.Bot({
 mobile: false, 
 token: process.env['tokendobot'], 
 prefix: ["seu prefixo"], 
 autoUpdate: false,
})
 
bot.onMessage() 
bot.loadCommands(`./Comandos/`)
