# Discord Bot Template 

*For those who want to Head Start with the code*

---

## Template Download and Setup 

To download this template you can use the download button or you can Copy and paste this following code in your Python file 😁

```
import discord
from discord import app_commands
intents = discord.Intents.default()
intents.message_content = True


client = discord.Client(intents=intents)

@client.event
async def on_ready():
    print("Logged in as {0.user}".format(client))



@client.event
async def on_message(message):
    if message.author == client.user:
        return

    if message.content.startswith('$hello'):
        await message.channel.send('Hello Brother !')


client.run('Bot Token')

```

Or you want to do the classic way of coding here you can do it 

## Old Classic Way 

# Check lists 
- [x] Install Python 
- [x] Git Setup(optional)
- [x] Git Clone or Download 
- [x] Installing the requirements to run the bot boi 
- [x] Bot creating and tocken !

# Install Python 
To run this bot you have to install python on your workstation.Install it Now [downloadmeboi](https://www.python.org/downloads/)

<br><br>

- [x] Install Python

## Git Setup(optional)

You can clone this repo using the git clone.Also one more thing is that you have to install git from your work station.[DownloadGitNowBoi](https://git-scm.com/downloads)

Once done Clone this repo by Pasting this command in your terminal 
```
git clone https://github.com/ilynivin/bottemplate.git
```

<br><br>

- [x] Git Setup(optional)

## Installing the requirements to run the bot boi 

Once you done your fancy way of cloning this repo you can run this bot boi by doing this facy adventure 

### <ins> Building the rope</ins>

Every Gamer / Programer / Webdevaloper Needs the basic framework . Eg : Gamer needs a keybord and mouse to show off epic skills

![epic](https://i.imgflip.com/3d32jg.jpg)

Ok! Now we show some epic HACKING SKILLS Like this 

![hackmeme](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSN1uSVzL70NrA1go5YydSQhdA5s78azK2G5wur91xy&s)

On your Terminal type this following Command 

```

pip install -r requirements.txt

```
And Onece it dones Run the `main.py`file in CLI
```
pyhton main.py
```

<br><br>

- [x] Installing the requirements to run the bot boi 

## Finally Its Time to Create Some Bots !

![bots](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvli_v0QP_3n65oToHibqpRWLzdmYWn8xwGbU9VYUvUA&s)

Go to discord dev portal and create a application and click create bot and copy the discord token and paste it on `client.run('your toc')`

*Note : Tocken are the password of the bot . If it comes in wrong hands it will become worse ! Make sure that your token is saved in `.env`file*


<br><br>

- [x]  Bot creating and tocken !

---

<h2 align = center> "Dont Fork it give it A Star 🎆"</h6>
