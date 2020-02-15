# ZeroCord Database

[![NPM](https://nodei.co/npm/zerocord.db.png)](https://nodei.co/npm/zerocord.db/)

ZeroCord.db is a simple sqlite database that allows you to interact with databases with 0 knowledge.

---

- [ZeroCord's Website](https://zerocord.xyz/)
- [Join our Discord](https://discord.gg/JjQTQVp)

---

## Examples

```js
let Discord = require("discord.js");
let db = require("zerocord-db");

let prefix = args.joins(" ");

db.set(`prefix.${message.guild.id}, prefix`);
```

---

## What's ZeroCord?

```
ZeroCord's database is a wrapper to use it for  better-sqlite3.
It's simple to use and for help new members
who are just getting into development.
```

```
All data in zerocord.db is stored persistently in a database.
Here is an example of setting an object in the database you will also 
need a file called json.sqlite.
```
