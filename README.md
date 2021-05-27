# Encourage Bot
#### ...a Discord Bot with Replit using Python and Flask

![yes-you-can-encourage-bot](yes-you-can-encourage-bot.jpg)

### Context:
A recent task from [1729](http://1729.com/) is to learn how to make a Discord Bot with Replit.

In the past I have created Discord Bot's but this time I found this exercise interesting as I didn't have find or rent or lease a computer to host my Discord Bot.

Everything was done within Replit using Python and Flask.

And to make it even more interesting I managed to use service such as Uptime Robot to keep my Bot alive.

### Commands:
- **$inspire**: displays a encouraging quote.
- **<plain english sentence with a [sad] word>**: takes a sad word in a sentence and turn it around with a positive message.
- **$new <encouraging quote>**: add a new quote to the Bot's list.
- **$list**: displays the available list of quotes.
- **$del <index>**: deletes a quote, with the provided index, from the available list.

### Usage:

Type any of these commands in the Discord Server where you have added this Bot in the `#general` channel.

`$inspire`
```
encourage bot: I've always tried to go a step past wherever people expected me to end up. -Beverly Sills
```

`$new You are Brilliant!`
```
encourage bot: New encouraging message added.
```

`$list`
```
encourage bot: ObservedList(value=['You are great!', 'Good Day!', 'You are an angel!', 'You are Brilliant!'])
```

`$del 0`
```
encourage bot: ObservedList(value=['Good Day!', 'You are an angel!', 'You are Brilliant!'])
```

### Service Status
![encourage-bot-service-status](encourage-bot-service-status.png)

### Reference
- [1729-Learn-to-Make-a-Discord-Bot-with-Replit](https://1729.com/replit-discord/)
- [w3mone-github-encourage-bot](https://github.com/w3mone/encourage-bot)
- [w3mone-replit-encourage-bot-spotlight](https://replit.com/@w3mone/encourage-bot?v=1)
- [w3mone-encourage-bot-status](https://stats.uptimerobot.com/wgvgGiL6NG)