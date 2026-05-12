# 🖥️ MacroServer — Python Backend for MateZ

> *The server powering gamer connections behind the scenes.*

---

## 📖 About the Project

MacroServer is the **Python-based backend server** that drives the MateZ gamer matchmaking platform. It handles all server-side logic — managing user data, game ads, matchmaking records, and the global chat — storing and serving everything via a connected database.

This is part of the **MateZ ecosystem**.

---

## 🏗️ Role in the Ecosystem

```
MateZ iOS App (Swift / SwiftUI)
        ↓
MAcroClient (SwiftUI integration layer)
        ↓
MacroServer ← YOU ARE HERE
(Python Backend + Database)
```

| Component | Role |
|---|---|
| [MateZ](https://github.com/Aryan-garg-1/MateZ) | iOS front-end app |
| [MAcroClient](https://github.com/Aryan-garg-1/MAcroClient) | Client-server integration layer |
| **MacroServer** | Python backend + database |

---

## ✨ What It Handles

- 👤 **User management** — profiles, registration, authentication
- 📢 **Ads system** — store and serve gamer ads (game, device, squad size)
- 🔍 **Matchmaking data** — connect players based on game and device filters
- 🌍 **Global chat** — real-time messaging data for the MateZ community
- 🗄️ **Database operations** — all CRUD operations for the MateZ platform

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Language** | Python |
| **Framework** | *(Server framework used)* |
| **Database** | *(Database used)* |
| **Client** | MAcroClient (SwiftUI) |
| **Version Control** | Git · GitHub |

## 🔗 Related Repositories

- [MateZ](https://github.com/Aryan-garg-1/MateZ) — The main iOS gamer matchmaking app
- [MAcroClient](https://github.com/Aryan-garg-1/MAcroClient) — The SwiftUI client layer

---

## 📬 Contact

**Aryan Garg** — [LinkedIn](https://linkedin.com/in/aryan-garg-029b41233) · [GitHub](https://github.com/Aryan-garg-1) · naryagarg@gmail.com
