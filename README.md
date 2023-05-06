# koa-browser-bot

A middleware used to determine the req whether it is a browser bot.

## usage

```bash
yarn add koa-browser-bot
```

Then, you can use `ctx.bot` (String) to get the browser bot. If it is a empty string, it`s a normal request.
