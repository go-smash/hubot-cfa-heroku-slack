# Hubot for Slack: Brigade Edition

This is a version of GitHub's Campfire bot, [Hubot](http://hubot.github.com/), which is designed to be deployed on [Heroku](http://www.heroku.com) with the [Slack adaptor](https://github.com/tinyspeck/hubot-slack).

This Hubot has been customized for being most useful to Code for America
brigades. At the moment, that means:

* Connected to Slack, the chat tool of choice for brigades.
* Includes the `hubot-cfa-brigade-checkin` script for event checkins
  from chat.
* More to come?

### Usage

The most straight-forward way to get up and running will assume that you
don't already have a Hubot connected to Slack.

1. Fork this repo.

2. (Optional) Make any changes you'd like.

3. _In your own repo._ click the **Deploy to Heroku** button below. The
   italicized part is particularly important if you made changes.

4. Use the form to configure and provision your Hubot. (You will need to
   open new tabs and visit other websites while filling it out.)

   **Note:** Don't forget name your Hubot something fun, or others will
judge you. At least I will. (The actual naming happens on Slack's system
when creating the API token.)

5. Once the Heroku app is created, consider connecting it to your GitHub
   repo and setting up auto-deploy on the `master` branch. This can be
done at your app's URL:
`https://dashboard.heroku.com/apps/YOUR-HUBOT-APP-NAME/deploy`

6. To wake Hubot up in the morning, [configure Heroku's scheduler addon
   according the the `hubot-heroku-keepalive` script's
README.](https://github.com/hubot-scripts/hubot-heroku-keepalive#waking-hubot-up)

The aforementioned **Deploy to Heroku** button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Notes

* Your brigade will not get automatic updates when this original repo is
  updated. If there are future changes, you will need to compare and
merge them into your own repo.

## License

[MIT](./LICENSE), just like the upstream [Hubot license](https://github.com/github/hubot/blob/master/LICENSE), so go :nut_and_bolt:s.
