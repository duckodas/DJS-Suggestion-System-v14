<h1 align="center">Welcome to Ducko's DJS Suggestion System V14</h1>
<h3 align="center">System made with 💖 by Ducko#7068</h3>

<div align="center">
 
[![discord](https://img.shields.io/discord/909261119103832084?style=for-the-badge&color=5865f2&label=Discord)](https://discord.gg/TKz7BMwEap)

[![issues](https://img.shields.io/github/issues/DuckoDas/DJS-Suggestion-System-v14?style=for-the-badge&color=d84559)](https://github.com/DuckoDas/DJS-Suggestion-System-v14)
[![stars](https://img.shields.io/github/stars/DuckoDas/DJS-Suggestion-System-v14?color=009F81&label=stars&style=for-the-badge)](https://github.com/DuckoDas/DJS-Suggestion-System-v14)
[![followers](https://img.shields.io/github/followers/DuckoDas?color=009F81&style=for-the-badge)](https://github.com/DuckoDas/)

**Advanced Suggestions System with Modals and Buttons**

**Upvote and Downvote button**

**Role to accept or decline or restart a suggestion!**

</div>
<hr>

## Features
- Custom colors for default the embed, accepted suggestions, and declined suggestions (Setup)
- Accept or decline or just start the suggestion again (Commands)
- Upvote or downvote a suggestion

## **Dependencies:**
- [Roald Modal Handler](https://github.com/RoaldDahl/Modal-Handler)
- [Roald Button Handler](https://github.com/RoaldDahl/Button-Handler)
- discord.js@14.3.0 or higher
- mongoose
- [MongoDB Database (FREE)](https://www.mongodb.com/)

## **Database Connection:**
```js
const { MongoDB } = require("MONGODB URL");
const { connect } = require("mongoose");

module.exports = {
  name: "ready",
  async execute(client) {
    connect(MongoDB).then(() => {
        console.log(`Mongoose Connected`);
    });
  },
};
```

## Little screenshot when a suggestion is sent:D
### Suggestion Preview
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022195798546591785/unknown.png)
### When Suggestion Preview
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022196236402577450/unknown.png)
### Voting on Suggestions Preview
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022196331353219113/unknown.png)
### Can't Vote on Different Suggestion Preview
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022196388156678226/unknown.png)
### Deleting Suggestions
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022196510533898260/unknown.png)
### Accepting Suggestions
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022196694512832512/unknown.png)
### Declining Suggestions
![Image](https://media.discordapp.net/attachments/1022195786064330842/1022199447943389194/unknown.png)


## **Credits:**
- [Roald Dahl](https://github.com/RoaldDahl/Modal-Handler) for helping + ideas
- [Telly](https://github.com/CantTelly) for testing + ideas
