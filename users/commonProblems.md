# Common problems
There are a few common problems that you may face while using Karen Bot. Some of these problems may be the creators fault, but most are due to Discord not liking my bot.

## Discord related issues

### Profile slash command doesn't work

So, the way the Discord API works, is that because I don't have an API intent (essentially extra privileges), Karen Bot can only access cached users (stored in memory). The problem with that approach is that if a person hasn't been cached (either by talking or getting mentioned), Karen Bot just <i>can't</i> access data for that user and the command fails.