<p align="center">
  <a href="README.md"><img src="assets/lang-en.svg" alt="English" height="60"></a>
  &nbsp;&nbsp;
  <a href="README.ru.md"><img src="assets/lang-ru.svg" alt="Русский" height="46"></a>
</p>

# Scout Bot 🤖

🔭 **Scout Bot** is a scout bot that scans **public** GitHub repositories, picks projects close to Velantrim's interests (🧠 AI memory, 🕸️ knowledge graphs, 💻 local-first, 🌍 open source), and prepares collaboration proposals.

> ⚠️ Scout Bot never sends anything on its own. Every proposal goes out only after the user's explicit "yes" to the specific text.

## 📁 Repository structure

```
scout-bot/
├── scanner/     # 🔎 reads public GitHub, read-only
├── filters/     # 🧹 selection filters and scoring
├── templates/   # 📝 approval card and message templates
├── consent/     # 🚦 explicit confirmation mechanism, log, opt-out list
└── config/      # ⚙️ weights, limits, topics; no tokens
```

## 🛠️ How it works

1. 🔎 **Search** — find public repositories on topics of interest.
2. 🧹 **Filters** — drop unsuitable ones (license, archived, fork, "do not contact" note, already contacted, opt-out list).
3. 📊 **Scoring** — rank the rest by relevance and activity.
4. 📂 **Dossier** — collect facts about the project, each with a link to its source.
5. ✍️ **Draft** — prepare a "What we found / What we propose" card and the message text.
6. ✅ **User approval** — the user reads the specific text and explicitly says "yes" or "no".
7. 📤 **Sending by the user** — the user sends the message, not the bot.
8. 🗃️ **Tracking replies and opt-outs** — record the outcome; an opt-out goes onto the opt-out list.

## 🚦 Explicit confirmation principle

- ✅ Every proposal goes out only after the user's explicit "yes" to the specific text.
- 🚫 No auto-consent.
- 🚫 No batch approval.
- ✏️ Any edit to the text = a new approval.
- ⏳ An approval is valid for 7 days.
- 🔒 The bot has no permission to send.
- 🛑 Opt-outs are respected forever.
- 📭 No emails are harvested from commits or profiles; project Issues or Discussions come first.

## 📨 Outreach log

📂 [`outreach-log/`](outreach-log/): who the Titan pitches were sent to and when, the rules, and open tasks (written in Russian). A new assistant should start with [`outreach-log/README.md`](outreach-log/README.md).

## 📌 Status

🚧 **In development** — design stage, implementation not started.

- RESEARCH ≠ IMPLEMENTATION
- IMPLEMENTED ≠ ACTIVATED

Everything above describes design principles, not working features.
