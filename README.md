# Slack bot using github actions

You can regularly send a message to slack using github actions.

## How to use

1. Create `SLACK_API_TOKEN` secret in your github repository.
    Set slack bot user token as `SLACK_API_TOKEN`.
    Get slack api token from [here](https://api.slack.com/apps)
1. Set the channel name where you want to send a message to `CHANNEL` in `send_message.py`.
1. Edit the message content `message` in `send_message.py`.
1. Schedule a workflow. Please edit `cron` parameter in `.github/workflows/send_message.yml`.
    You can also run a workflow manually in github.
