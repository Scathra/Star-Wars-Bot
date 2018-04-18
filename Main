import discord
from discord.ext.commands import Bot
from discord.ext import commands
import asyncio
import time
import sqlite3
import datetime
import random



@client.event
async def on_ready():
    print("Bot is ready!")

@client.event
async def on_message(message):
    userID = message.author.id
    if message.content == "I have the high ground!":
        await client.send_message(message.channel, "https://cdn.discordapp.com/attachments/392641034557063170/428523497459941376/Screen_Shot_2017-05-03_at_12.png")
    if message.content == "Do It!":
        await client.send_message(message.channel, "https://cdn.discordapp.com/attachments/392641034557063170/428523293528555521/36133724.png")
    if message.content == "Come to the Dark Side":
        await client.send_message(message.channel, ":cookie:")
    if message.content == "Ping":
        await client.send_message(message.channel, "<@%s> Pong!" % (userID))
    if message.content == "Luke":
        await client.send_message(message.channel, "I am your father.")
    if message.content == "Wicket":
        await client.send_message(message.channel, "That's *Grandmaster Jedi* Wicket to you.")
    if message.content == "Scathra":
        await client.send_message(message.channel, "The keeper of The Star Wars Faction's *correct* ways and leader of the Old Guard.")
    if message.content == "Perry":
        await client.send_message(message.channel, "Leader of The Star Wars Faction. Running it into the ground with his evil New Order ideals.")
    if message.content == "Gimme some money!":
        await client.send_message(message.channel, "What is this money? That should be implemented. Scathra you lazy bum! Get on that!")
    if message.content == "Scathra is dumb":
        await client.send_message(message.channel, "Actually I believe that you are the one that is a moron")
    if message.content == "Am I special?":
        if "400137076609253376" in [role.id for role in message.author.roles]:
            await client.send_message(message.channel, "Yes, you are very special.")
        else:
            await client.send_message(message.channel, "No, you suck.")
    if message.content == "SOUND THE ALARM!!!":
        if "418878236861136906" in [role.id for role in message.author.roles]:
            await client.send_message(message.channel, "@everyone, THE ALARM HAS BEEN SOUNDED! WOOP! WOOP! WOOP! ALL PERSONNEL TO BATTLE STATIONS, THIS IS NOT A DRILL! I REPEAT, THIS IS NOT A DRILL!")
        else:
            await client.send_message(message.channel, "Nope. You aren't cool enough to sound the alarm.")
    if message.content == "All clear":
        if "418878236861136906" in [role.id for role in message.author.roles]:
            await client.send_message(message.channel, "@everyone, threat neutralized. Alarm has been turned off.")
        else:
            await client.send_message(message.channel, "Nope. you're stupid you know that? This threat is serious and you just want to shut it off?")
    if message.content == "Rainsford":
        await client.send_message(message.channel, "Grumpy person who hates getting pinged. Also a spoil sport.")
    if message.content == "HALP!!!":
        await client.send_message(message.channel, "List of commands you can use: How gay?, I have the high ground!, Do It!, Come to the Dark Side, Ping, Luke, Wicket, Scathra, Perry, Rainsford, HALP!!!, Gimme some money!, Scathra is dumb, Am I special?, BANK HALP!!!. Admin only commands: ADMIN PERKS!!!, SOUND THE ALARM!!!, All clear")
    if message.content == "How gay?":
        if message.author.id == "384450469981847562":
            await client.send_message(message.channel, "Damn! You pretty gay!")
        else:
            await client.send_message(message.channel, "Not as gay as Scathra.")
    if message.content == "ADMIN PERKS!!!":
        if "418878236861136906" in [role.id for role in message.author.roles]:
            await client.send_message(message.channel, "Aw hell yeah!")
        else:
            pass
    if message.content == "BANK HALP!!!":
        await client.send_message(message.channel, "Sorry but the First Galactic Bank is currently under construction. Please check back at a later date. Appologies for the inconvenience.")
    if message.content == "super secret":
        await client.send_message(message.channel, "WOW! <@%s> has found the super secret command! Congratulaitons! <@384450469981847562>,you know what to do." % (userID))
    if message.content == "no":
        if message.author.id == "384450469981847562":
            await client.send_message(message.channel, "He said no!")
        else:
            pass
                                      









client.run("NDI4MzE5MDUzNzMyNTExNzUw.DZxeNg.0C_MqBy3QS67AfUrzuHTiWqcd6M")
