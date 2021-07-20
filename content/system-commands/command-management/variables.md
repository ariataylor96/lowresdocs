---
weight: -1
---

Some variables are available for you to use in your commands. To use a variable, surround its name in curly braces (`{}`) in your command body. For instance, to add a lurk command, you would do as follows:

```
!addcommand lurk Enjoy your lurk, {sender}!
```

The variables you have available are as follows:

 - `sender` - the username of the person that sent the message
 - `channel` - the name of the streamer whose chat the message was sent in
 - `argsString` - everything following the command invocation
   - For `!hello everyone in chat`, `argsString` would be `everyone in chat`
 - `command` - the command being called, such as `!lurk`
 - `count` - the number of times this command has been called

More variables will be added as needed and at Nickel's request. They will be documented here when they are.
