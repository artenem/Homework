import discord
from discord.ext import commands
import random

intents = discord.Intents.default()
intents.message_content = True

bot = commands.Bot(command_prefix='$', intents=intents)

@bot.command()
async def number(ctx):
    n = random.randint(1, 100)
    await ctx.send(n)

@bot.command()
async def rainbow_color(ctx):
    colors = ['Красный', 'Оранжевый', 'Жёлтый', 'Зелёный', 'Голубой', 'Синий', 'Фиолетовый']
    r = random.choice(colors)
    await ctx.send(r)

bot.run("MTIxNzg4NDY5NzMwNTAyNjcxMw.G5cPr3.PlrRVA3A2w4OMshouOZ_7IY3veQhcnWuuUN1nU")
