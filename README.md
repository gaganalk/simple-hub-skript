Here's a fixed and polished version of your `README.md` snippet, including the correct image tag and continuation of the content. I also corrected minor grammar and structure issues:

---

```
<p align="center">
  <img src="https://media.discordapp.net/attachments/1281345499256983614/1367922666161573990/GuF7VP5.png?ex=681658c2&is=68150742&hm=efda4b8303c9b991caf7a9c61e24f0798f5e5c505acd252d3d3e6e8750e09878&=&width=749&height=75" alt="Typing Animation"/>
</p>

# ⛩ Simple /Hub Skript
A simple Skript that sends players to your **Hub/Lobby** server using commands like `/hub`, `/lobby`, and `/server hub`.  
Created by **ArX Studios × gaganalk**

---

## 🔧 Features
- ✅ Supports `/hub`, `/lobby`, and `/server hub` commands.
- 🚀 Works with most proxy systems (e.g., **Velocity**, **BungeeCord**).
- ⚙️ Fully customizable (`"joinq hub"` can be replaced with `"server hub"` or any other).
- 💬 Sends action bar messages and plays a sound when used.
- 🪶 Lightweight, simple, and user-friendly.

---

## 📦 Installation
1. Place the `hub.sk` file inside your `plugins/Skript/scripts/` directory.
2. Run `/sk reload hub` in-game or via console, or restart your server.

---

## 🛡️ Command Hider Plugin Notice
If you're using any plugin that hides or restricts commands (like the following):

- **CommandWhitelist**
- **PL-Hide**
- **ServerSecurity**
- **Any command filter/hider plugin**

➡️ You **must whitelist** the following commands:
```

/hub
/lobby
/server hub

````

---

## 🧪 Customization Tip
Using another proxy system or plugin?

Just edit this line in the Skript:
```skript
execute player command "joinq hub"
````

And replace it with:

```skript
execute player command "server hub"  # or your custom command
```


## 🔊 Player Feedback

Players receive:

* 📜 A message: `Sending you to the Hub Server!`
* 🎵 A sound: `block.note_block.banjo`


## 📜 License & Credit

* ✅ **Feel free to modify or extend** this Skript for your server.
* ❗ **Please do not remove credits** to **ArX Studios × gaganalk**.
* 📢 You're welcome to share, post, and fork it with proper credit.

---

## ✨ Credits

**Author:** [gaganalk](https://github.com/gaganalk)
**Team:** ArX Studios
**Discord:** `gaganalk`

```
