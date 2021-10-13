# discord-bot-Client-missing-intents
So i have been trying to make a discord bot and whenever i do node . in the terminal of VS it comes up with an error message if someone could help that would be great 
the code is below

const Discord = require('discord.js'); 

const bot = new Discord.Client(); 

const token = 'My token'; 

bot.on('ready', () =>{
        console.log('bot online');
    }) 
bot.on('message' , msg=>{ 
    if(msg.content === 'hello'){
       msg.reply('hi this is Zaks tunez bot'); 
    }
})
Bot.login(token)
