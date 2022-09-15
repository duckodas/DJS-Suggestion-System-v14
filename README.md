<h1 align="center">Welcome to Ducko's DJS Suggestion System V14</h1>
<h3 align="center">System made with 💖 by Ducko#7068</h3>

<div align="center">
  
[![issues](https://img.shields.io/github/issues/DuckoDas/DJS-Suggestion-System-v14?style=for-the-badge&color=d84559)](https://github.com/DuckoDas/DJS-Suggestion-System-v14)
[![stars](https://img.shields.io/github/stars/DuckoDas/DJS-Suggestion-System-v14?color=009F81&label=stars&style=for-the-badge)](https://github.com/DuckoDas/DJS-Suggestion-System-v14)
[![followers](https://img.shields.io/github/followers/DuckoDas?color=009F81&style=for-the-badge)](https://github.com/DuckoDas/)

</div>
<hr>

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
![Image](https://media.discordapp.net/attachments/1017511503139704852/1019974357885395017/unknown.png)

## **Credits:**
- [Roald Dahl](https://github.com/RoaldDahl/Modal-Handler) for helping + ideas
- [Telly](https://github.com/CantTelly) for testing + ideas
