# gitlab-bot

gitlab bot that listen to gitlab webhooks and send pipeline and jobs events to the telegram chat

## usage

```shell script
docker build -t gitlab-bot .
docker run -it -p 5000:5000 -e TOKEN=<token> -e CHAT_ID=<chat-id> -d gitlab-bot
```
create gitlab webhook with no auth that points to your bot
