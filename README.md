<div align="center">
<img src="https://images5.alphacoders.com/911/911614.png" alt="MARSBot" width="500" />

# MARSBot

> MARSBot is a multipurpose WhatsApp bot using wa-automate-nodejs library!
>
>



<details>
  <summary>Contact me!</summary>

  [Instagram](https://www.instagram.com/m_arifin_syam)

</details>

</div>

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker GIF command)
* Any text editor

# Installation
## 📝 Cloning this repo
```bash
> git clone https://github.com/SlavyanDesu/BocchiBot
> cd BocchiBot
```

## ✍️ Editing the file
Edit the required value in `config.json`.
```json
{
    "ownerBot": "62812xxxxxxxx@c.us", 
    "prefix": "$",
    "uaOverride": "WhatsApp/2.2037.6 Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.83 Safari/537.36",
    "token": "api-key",
    "nao": "api-key",
    "vhtear": "api-key"
}
```

`ownerBot`: your WhatsApp number.  
`prefix`: bot's prefix.  
`uaOverride`: your user agent.  
`token`: API token. You can get it [here](https://api.i-tech.id) by creating an account. After that, set your server/host static IP in [here](https://api.i-tech.id/settings/profile).  
`nao`: SauceNAO API token. You can get it [here](https://saucenao.com/user.php) by creating an account.  
`vhtear`: VHTear API token. You can get it [here](https://api.vhtear.com/) by purchasing his API key.   

## 🗣️ Changing language
If you want to change the language, replace all `ind` function to `eng`.   
Example:
```js
ind.wrongFormat()
```
To:
```js
eng.wrongFormat()
```

## 🔍 Installing the dependencies
```bash
> npm install
```

## 🆗 Running the bot
Regular node:
```bash
> npm start
```

PM2:
```bash
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```bash
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

After that scan the QR code using your WhatsApp apps in your phone!

# Features
If you want to unlock premium commands, please contact me~

|   Unique Features   |  Conditions  |
| :-----------------: | :----------: |
| Register            |      ✔️      |
| Leveling            |      ✔️      |

|     Sticker Maker     | Availability |
| :-------------------: | :----------: |
| Send/reply image      |      ✔️      |
| Send/reply GIF        |      ✔️      |
| Send/reply MP4        |      ✔️      |
| Text to sticker       |      ✔️      |
| Text to sticker GIF   |      ✔️      |
| Sticker to image      |      ✔️      |

|      Downloader     | Availability |
| :-----------------: | :----------: |
| Facebook video      |      ✔️      |
| YouTube audio/video |      ✔️      |
| Joox                |      ✔️      |

|       Misc       | Availability |
| :--------------: | :----------: |
| Say              |      ✔️      |
| Lyric            |      ✔️      |
| Shortlink        |      ✔️      |
| Wikipedia        |      ✔️      |
| KBBI search      |      ✔️      |
| IG stalk         |      ✔️      |
| GSMArena         |      ✔️      |
| Food receipt     |      ✔️      |
| YouTube search   |      ✔️      |
| TTS              |      ✔️      |
| AFK              |      ✔️      |
| Distance         |      ✔️      |
| Find Sticker     |      ✔️      |
| List surah       |      ✔️      |
| Surah            |      ✔️      |

|        Fun       | Availability |
| :--------------: | :----------: |
| Harta tahta      |      ✔️      |
| Calender         |      ✔️      |
| Weton jodoh      |      ✔️      |
| Zodiac           |      ✔️      |
| Write            |      ✔️      |
| Missing person   |      ✔️      |
| Valentine        |      ✔️      |
| Glitch Text      |      ✔️      |
| SimSimi          |      ✔️      |
| Blackpink logo   |      ✔️      |
| Pornhub logo     |      ✔️      |

|      Weeb Zone     | Availability |
| :----------------: | :----------: |
| Neko               |      ✔️      |
| Wallpaper          |      ✔️      |
| Kemono             |      ✔️      |
| Kusonime           |      ✔️      |
| Komiku             |      ✔️      |
| Anime tracer       |      ✔️      |
| Source finder      |      ✔️      |
| Random waifu       |      ✔️      |

|        Bot       | Availability |
| :--------------: | :----------: |
| NSFW toogle      |      ✔️      |
| Bot stats        |      ✔️      |
| List block       |      ✔️      |
| Ping             |      ✔️      |
| Delete           |      ✔️      |
| Report bug       |      ✔️      |
| Group join       |      ✔️      |

|        Owner       | Availability |
| :----------------: | :----------: |
| Broadcast          |      ✔️      |
| Clear all messages |      ✔️      |
| Leave all groups   |      ✔️      |
| Get session        |      ✔️      |
| Ban                |      ✔️      |
| Evaluates JS       |      ✔️      |
| Shutdown           |      ✔️      |
| Add premium user   |      ✔️      |
| Set status         |      ✔️      |

|    Moderation    | Availability |
| :--------------: | :----------: |
| Add              |      ✔️      |
| Kick             |      ✔️      |
| Promote          |      ✔️      |
| Demote           |      ✔️      |
| Leave            |      ✔️      |
| Everyone         |      ✔️      |
| Toogle NSFW      |      ✔️      |
| Set group icon   |      ✔️      |
| Anti-link        |      ✔️      |
| Welcome          |      ✔️      |
| Auto-sticker     |      ✔️      |
| Mute group       |      ✔️      |

|        NSFW        | Availability |
| :----------------: | :----------: |
| Lewds              |      ✔️      |
| nHentai lookup     |      ✔️      |
| Fetish             |      ✔️      |
| Latest Nekopoi     |      ✔️      |
| Waifu NSFW         |      ✔️      |
| Pornhub downloader |      ✔️      |
| Waifu 18+          |      ✔️      |
| nHentai downloader |    Premium   |
| Multi lewds        |    Premium   |
| Multi fetish       |    Premium   |

# Thanks to
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* [`YogaSakti/imageToSticker`](https://github.com/YogaSakti/imageToSticker)
* [`uukina`](https://github.com/uukina)
* [`MrPawNO`](https://github.com/MrPawNO)
* [`Pahri123`](https://github.com/Pahri123)
* [`LeviathanH`](https://github.com/LeviathanH)
* [`ferlitopym`](https://github.com/ferlitopym)

# License
**BocchiBot** © [SlavyanDesu](https://github.com/SlavyanDesu), released under the MIT License.
Authored and maintained by SlavyanDesu.

<p align="center">
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FSlavyanDesu%2FBocchiBot?ref=badge_large"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FSlavyanDesu%2FBocchiBot.svg?type=large" />
</p>  
