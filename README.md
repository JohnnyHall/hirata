<p align="center">
  <img src="https://i.imgur.com/cGbZ5Ez.png" height='300'/>
</p>

# 🎶 Hirata
> Hirata is a discord music bot

## 📜 Requirements
1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. Node.js 16.11.0 or newer

## ⚙️ Installation
```sh
git clone https://github.com/eritislami/evobot.git
cd evobot
npm install
```
After installation finishes follow configuration instructions then run `npm run start` to start the bot.

## ⚙️ Configuration
Copy or Rename `config.json.example` to `config.json` and fill out the values:
⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "!",
  "PRUNING": false,
  "LOCALE": "en",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```
## 📝 Features & Commands
> Note: The default prefix is '!'

- 🎶 Play music from YouTube via url

`!play https://www.youtube.com/watch?v=GLvohMXgcBo`

- 🔎 Play music from YouTube via search query

`!play under the bridge red hot chili peppers`

- 🎶 Play music from Soundcloud via url

`!play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

- 🔎 Search and select music to play

`!search Pearl Jam`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

- 📃 Play youtube playlists via url

`!playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

- 🔎 Play youtube playlists via search query

`!playlist linkin park meteora`

- Now Playing (!np)
- Queue system (!queue, !q)
- Loop / Repeat (!loop)
- Shuffle (!shuffle)
- Volume control (!volume, !v)
- Lyrics (!lyrics, !ly)
- Pause (!pause)
- Resume (!resume, !r)
- Skip (!skip, !s)
- Skip to song # in queue (!skipto, !st)
- Move a song in the queue (!move, !mv)
- Remove song # from queue (!remove, !rm)
- Play an mp3 clip (!clip song.mp3) (put the file in sounds folder)
- List all clips (!clips)
- Show ping to Discord API (!ping)
- Show bot uptime (!uptime)
- Toggle pruning of bot messages (!pruning)
- Help (!help, !h)
- Command Handler from [discordjs.guide](https://discordjs.guide/)
- Media Controls via Reactions
  
## 🌎 Locales
Currently available locales are:
- English (en)
- Arabic (ar)
- Brazilian Portuguese (pt_br)
- Czech (cs)
- Dutch (nl)
- French (fr)
- German (de)
- Greek (el)
- Indonesian (id)
- Italian (it)
- Japanese (ja)
- Korean (ko)
- Minionese (mi)
- Persian (fa)
- Polish (pl)
- Russian (ru)
- Simplified Chinese (zh_cn)
- Singaporean Mandarin (zh_sg)
- Spanish (es)
- Swedish (sv)
- Traditional Chinese (zh_tw)
- Thai (th)
- Turkish (tr)
- Ukrainian (uk)
- Vietnamese (vi)

## 🤝 Contributing
1. [Fork the repository](https://github.com/JohnnyHall/hirata/fork)
2. Clone your fork: `git clone https://github.com/JohnnyHall/hirata.git`
3. Stage changes `git add .`
4. Commit your changes: `cz` OR use `git commit`
5. Submit a pull request

## 🤝 Related Projects
[Base Repository](https://github.com/eritislami/evobot)

## 👤 Developers
 - João Victor Rokemback Tápparo

<p align="center">
  Created on <br>
  04/08/2022
</p>
