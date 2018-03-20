
![](https://hubot.github.com/assets/images/layout/hubot-avatar@2x.png)
## Mission

Using Hubot, write a bot that automagically replies to specific words on the Ryver chatroom.

## Documentation and code you will need

- [Ryver API](http://support.ryver.com/ryver-apis-overview/)
- [HUBOT](https://hubot.github.com/) : Hubot is your friendly robot sidekick. Install him in your company to dramatically improve employee efficiency.
- [RyverApp/hubot-ryver](https://github.com/RyverApp/hubot-ryver) : Hubot adapter for Ryver


## info you will need 

```
HUBOT_RYVER_USERNAME: @hubot
HUBOT_RYVER_PASSWORD: Y0L000Yeah!
HUBOT_RYVER_APP_URL : becode.ryver.com
```

## things it should do

Basically, autoreply to keywords with useful information. 

For example :

`whereami` -> launch google maps  
`late` -> creates a reply with this message :   
> Don't forget to send beforehand an email to your coaches and admin@becode.org to inform them that you will be absent / late.
`github`-> autoreply github.com/becodeorg .
`help`-> the available list of commands.

Feel free to add more ideas, like :

`joke` -> fetches a joke from a joke web service
`kitten`-> fetches a kitten Gif from a kitten web service.
...


## Deliverable
- A repository with the needed code and the proper instructions to set it up along with configuration option explanations.
- The bot script running on heroku  https://hubot.github.com/docs/deploying/heroku/
![](https://hubot.github.com/assets/images/layout/schematic.svg)
