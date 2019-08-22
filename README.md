Siara Simple Slack Bot
======================

# About

Simple Slack Bot which responds to slash command `/siara`

# Installation

## Heroku

You can deploy it wherever you want. I've used Heroku for example.
Create an app at https://dashboard.heroku.com/apps and push it:

```bash
$ heroku login
$ heroku git:remote -a my-bot-name
$ git push heroku master
```

## Slack

Create new app in Slack at https://api.slack.com/apps
Add Slash Command `/siara` with Request URL pointing
to your app instance, eg. https://my-bot-name.herokuapp.com/

# Credits

Based on SiaraBot by Michal Pieniazek https://github.com/michaelmoney/SiaraBot
