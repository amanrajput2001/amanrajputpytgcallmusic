# amanrajputpytgcallmusic
this is an op music pyrogram music bot..... this bot user music bot can play music   without being admin......
# TG-MusicPlayer
A Telegram Userbot to play Audio and Video songs / files in Telegram Voice Chats.


It's made with [PyTgCalls](https://github.com/pytgcalls/pytgcalls) and [Pyrogram](https://github.com/pyrogram/pyrogram)


## Requirements
- Python 3.8+
- FFMPEG
- Nodejs v16+


## Deployment

### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
### Railway 
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Famanrajput2001%2Famanrajputpytgcallmusic&envs=API_HASH%2CAPI_ID%2CGROUP_MODE%2CHNDLR%2CSESSION&API_HASHDesc=my.telegram.org&API_IDDesc=my.telegram.org&GROUP_MODEDesc=Anyone+can+play%2C+if+set+to+True.+Set+it+to+False+to+restrict+play+access+to+Sudo+Users%2FContacts+only&HNDLRDesc=Handler+%7C+Default+%28%21%29&SESSIONDesc=Pyrogram+String+Session&HNDLRDefault=%21&referralCode=Vr-DSL)
### Local Deploy
1) Installing NodeJS
```bash
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs


2) Installing FFMPEG and Git
```bash
sudo apt-get install git ffmpeg -y
```

3) Cloning the Repo
```bash
https://github.com/amanrajput2001/amanrajputpytgcallmusic
```

4) Rename `example.env` to `.env` and Fill in the Environment Variables

5) Installing Requirements
```bash
pip3 install -U -r requirements.txt
```

6) Run the Bot
```bash
python3 main.py
```


## Environment Variables
- `API_ID`
- `API_HASH`
- `SESSION` - A Pyrogram String Session. Get one from [Here](https://replit.com/@dashezup/generate-pyrogram-session-string)
- `HNDLR` - Your Userbot Handler (Default is !)
- `GROUP_MODE` - if Value is set to `True`, Anyone can Play. Set it to `False` to restrict play access to Sudo Users/Contacts only.


## Commands and Usage
1) Start the Userbot, check if the Userbot is running by `!ping`.
2) Commands of this userbot are accessible to and can be used by the Account itself and it's Contacts.
3) Check `!help` for commands.


## Credits ✨
- [null] for [Pyrogram](https://github.com/amanrajput2001/amanrajputpytgcallmusic)https://github.com/amanrajput2001/amanrajputpytgcallmusic
- [null] for [PyTgCalls](https://github.com/amanrajput2001/amanrajputpytgcallmusic)
