# litecoin-tip-bot

A twitter bot for tipping users with litecoin. Inspired by [tippr](https://www.reddit.com/r/tippr/wiki/index).

Starting off with a naïve implementation and working from there.

## Installation

Make sure you have the latest versions of node and npm.

```
git clone https://github.com/timothyylim/litecoin-tip-bot.git
cd litecoin-tip-bot
npm install
node index
```

Run tests

```npm run test```

## Todos:

Firstly we need to create a functional twitter bot that can:
- [ ] Be notified when it is mentioned i.e. @litecoin-tippr
  - [ ] Only when that mention is a reply to a tweet
- [ ] Respond to a mention
- [ ] Be notified when sent a direct message
- [ ] Respond to a direct message

Later we'll hook up the User class and the DB and test accordingly.

## Questions

## Longer term

- [ ] Devops stuff to make sure the service is robust
- [ ] Decide on whether to make this a litecoin tipbot or a lightning network tipbot
- [ ] Replace callbacks in DB with [async/await](http://yizhang82.me/async-sqlite-as-promise)

## Resources:
- [bitcoin cash recovery tool](https://github.com/timothyylim/bitgo-bcash-recovery-tool/tree/master/src)
- [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib)
- [blocktrail slack tip bot](https://github.com/blocktrail/slack-tipbot/blob/master/lib/user.js)
