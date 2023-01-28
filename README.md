<h1 align="center">SelfBot</h1>

<p align="center">
  <a href="https://github.com/rinxyzz/SelfBot/"><img src="https://img.shields.io/github/last-commit/rinxyzz/SelfBot?style=flat" /></a>
  <a href="https://github.com/rinxyzz/SelfBot/"><img src="https://visitor-badge.laobi.icu/badge?page_id=Mewzax.Discord-Selfbot-RPC" /></a>
  <img alt="GitHub Workflow Status (with branch)" src="https://img.shields.io/github/actions/workflow/status/rinxyzz/SelfBot/codeql.yml?branch=main">
 
  <br>
  <b>The most efficient Discord RPC you'll ever find.</b><br>
  Made with ❤ by <b><a href="https://github.com/Rinxyzz">Rinzxx</a></b>
  <br>
  If you liked this project, please consider <b>starring</b> it <3
</p>

---

 ## Why is Discord-Selfbot-RPC better than other Discord RPC ?

> because it don't need to have Discord running in background / Free Hosting on replit.com 24h/7 / more features

![image](https://media.discordapp.net/attachments/1068223147955998740/1068750623006281758/Screenshot_20230128_112636.png?width=240&height=468)


### Features:

- Spotify RPC
- Game RPC
- Twitch RPC
- Custom Status: online, dnd, idle
![image](https://cdn.discordapp.com/attachments/1068223147955998740/1068750809422119042/Screenshot_20230128_112215.png)

# Installation
## Setting up the Client ID
- Create an app on Discord Devlopers Portal
- Go to OAuth2 and copy the CLIENT ID
- Open config.json replace where it says applicationID at the bottom with the Client ID you copied
## Adding Images
Once you have done that you can start adding images for your Rich Presence

- Navigate back to the Discord Devlopers Portal
- Press Rich Presence in your application then
- Click Art Assets then scroll down and you will see Add Image(s)
- Click that then chose an image and name
- Click Save to save your changes

**(excluding APP Name read above for info)**

**(The image sections in the config.json would be the names of the images you uploaded to your app on Discord Devlopers Portal)**
![image](https://camo.githubusercontent.com/d73bb456ba14d7d58bccfaa272e05aa4bc3cb1f7da2a7f92b6533b4d6e3d7f49/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3738393030373035363234343833343330342f3833353033353631323534353135353130322f6669782e706e67)
![image](https://camo.githubusercontent.com/fd9e63ce894342f9bcf4b3d5aed498ecee0574cc92968f2213717e3b87988a8c/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3732393838383937363331353631333332372f3833353033363831333737363132353937322f646f6e652e706e67)

# Host On Replit
- Fork the repository
- Go to https://www.replit.com
- Create an account
- Fork your project at https://replit.com/github
- Edit config.json
- Go to "Secrets environment variables"
- Create the variable TOKEN and put your token
RUN

# FAQ 
### - How to import spotify images 
- Connect to a spotify account on browser and create a playlist with the image you want
- Go to https://developer.spotify.com/console/get-playlist-images/
- Open your playlist in browser and copy the ID next https://open.spotify.com/playlist/
- Put your ID in https://developer.spotify.com/console/get-playlist-images/
- Push GET TOKEN button
- Autorize the app to get your token
- Push TRY IT button
- Use it in the config file:
```
largeImageKey: "spotify:YOUR-URL"
```

<br />

# How To Make Keep Alive
Uptime Robot is all about helping you to keep your websites up. It monitors your websites every 5 minutes and alerts you if your sites are down.
> its 100% free It will keep your server up until your server ran into problems.

UptimeRobot setup Once you log into your UptimeRobot account.
> Go to Dashboard (default screen for uptimerobot is dashboard) To add new link. Click Add New Monitor

![image](https://camo.githubusercontent.com/c09d7680c8ee97d9c84d6b66d45bbb47a6f9125236a0acb98ef64f035a4935d7/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303435373935325f62303034663032623166636335633465626266643964643461633665373261332e706e)
Once you click that. This Screen will popup:
![image](https://camo.githubusercontent.com/b49e3cd4eb7d9706cb48c11f5e91d87a5ab83a78b848df8825588c2b301d8484/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303539313630395f36333732656333326632306133623965363938633664313730363536303865642e706e)
Now Select Monitor type HTTP(s).
> Make sure type is HTTP(s) not ping or other

Now details popped up like these
![image](https://camo.githubusercontent.com/02b46d97454f8b5e42c7b569182cb98133ef8e86ef6d2213293429f86ddc7d9c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303631343230395f63616233636661313230346235663530303364646634383038666131363664372e706e)
For Friendly Name enter what would you like to call your Monitor. For URL (or IP) enter your web server link.

> if you're using repl, it should look like this https://your-repl-name.your-username.repl.co, but with your repl name.

For Monitoring Interval, I'll suggest leaving it to the default value.

Now if you have all the info done. your page should look like this
![image](https://camo.githubusercontent.com/d42c1f1ae2291856612dff223109121ada4c834889ffd57f933a9e2493b2784b/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303633383837315f61373131656132366231363331306335323637396439633334366432313232312e706e)
Now you also have this box:
![image](https://camo.githubusercontent.com/df78c63596c4b4909ac6298685896c92ad9c1af9232ab668cd3c639b921c98f8/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303738393533335f63653436396131323539636533376266613135663430663035633232393131632e706e)
> This means that if you select this, and your server is down or ran into any problems. UptimeRobot will alert you by sending an email. I suggest you add alert notify

Now click Create Monitor You have successfully created a monitor. Now your server will stay online, even if you're not running your code.

On your dashboard, your monitor will appear:
![image](https://camo.githubusercontent.com/546e6fb18cdda7d40b2ce888a9e9f97f154addb948c6452438d159383ab513c7/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303730373039315f38633631313461636561666634343865643337613238303239646138643363312e706e)
as you see, it showing that your server is down. Your server is not down. To fix this just give it 1-2 min and reload your page.
![image](https://camo.githubusercontent.com/3309ea7f87a91e03f8cd66a8b9e0f9f41a65afcecd8f4343087a3e604b254ecd/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f7265706c69742f696d616765732f313534333730303732343335365f63353635376236646338333730366662343637363061386666386434616362372e706e)
There you go! Your Monitor is running.
### Disclaimer
```
Using a selfbot is against TOS and can get your account banned. Use it at your own risks.
```
