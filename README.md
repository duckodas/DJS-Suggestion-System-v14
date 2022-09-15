<h1 align="center">Welcome to Ducko's DJS Suggestion System V14</h1>
<h3 align="center">System made with 💖 by Ducko#7068</h3>

<div align="center">

[![discord](https://img.shields.io/discord/909261119103832084?style=for-the-badge&color=5865f2&label=Discord)](https://discord.gg/TKz7BMwEap)
  
[![issues](https://img.shields.io/github/issues/DuckoDas/DuckoDas?style=for-the-badge&color=d84559)](https://github.com/DuckoDas/DJS-Suggestion-System-v14)
[![stars](https://img.shields.io/github/stars/duckodas?color=009F81&label=stars&style=for-the-badge)](https://github.com/DuckoDas/DJS-Suggestion-System-v14)
[![followers](https://img.shields.io/github/followers/DuckoDas?color=009F81&style=for-the-badge)](https://github.com/DuckoDas/)

</div>
<hr>

## **Dependencies:**
- [Roald Modal Handler](https://github.com/RoaldDahl/Modal-Handler)
- [Roald Button Handler](https://github.com/RoaldDahl/Button-Handler)
- discord.js@14.3.0
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

## **Credits:**
- [Roald Dahl](https://github.com/RoaldDahl/Modal-Handler) for helping + ideas
- [Telly](https://github.com/CantTelly) for testing + ideas
