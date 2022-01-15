# 📰 CyberFeeds - CyberSec News Delivery Discord Bot

CyberFeeds is a discord bot that's intended to deliver Cyber Security related news. I use it for my [SiphySec](https://dsc.gg/siphysec) Discord Server. With over 3000 articles delivered in the year, so far it's been very reliable and helpful! It's a self-host clone of the [MonitoRSS](https://monitorss.xyz/) bot, hosted on heroku 24/7 a month for free!

![image](https://user-images.githubusercontent.com/52672162/149633261-71e1f1b5-7f89-4115-ae4d-e39e4bcc128c.png) ![image](https://user-images.githubusercontent.com/52672162/149632977-124d521a-3d97-40a3-bc33-868f734cc159.png)  
![image](https://user-images.githubusercontent.com/52672162/149633313-3ad35f0e-2e2f-4395-afc5-1a3d89647096.png)


# MonitoRSS Clone (Formerly Discord.RSS)

> The main repository is located at https://github.com/synzen/MonitoRSS,  
> and the web repository at https://github.com/synzen/MonitoRSS-Web.

Driven by the lack of comprehensive RSS bots available, I have decided to try my hand at creating one of my own. Designed with as much customization as possible for both users and bot hosters, while also (or should be) easy to understand.

All documentation can be found at https://docs.monitorss.xyz/.

### Publicly Hosted Instance

Don't want to bother hosting your own instance? Use the publicly hosted one!

https://discordapp.com/oauth2/authorize?client_id=268478587651358721&scope=bot&permissions=19456


### Web Interface

MonitoRSS also comes with a web interface! To run the web interface, see the documentation.

<img src="https://i.imgur.com/CD8mbRh.png" width=700/>

### Deploy to Heroku

You can deploy the bot in a simple way to Heroku using the button below. [Click here for detailed instructions](https://github.com/synzen/MonitoRSS/issues/45) - **you must have MongoDB hosted with its URI ready to also insert into `DRSS_DATABASE_URI` environment variable**.

<!-- [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy) -->

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https://github.com/synzen/MonitoRSS-Clone&template=https://github.com/synzen/MonitoRSS-Clone/tree/master)

*If you want to deploy manually without the button, you can [follow this guide instead](https://github.com/synzen/MonitoRSS/issues/95).*
