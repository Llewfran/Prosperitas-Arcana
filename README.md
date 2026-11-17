# Prosperitas Arcana

Companion app for the Prosperitas Arcana board game: private order sheets, staged resolution and Gold settlement, with bot opponents.

**Play:** https://llewfran.github.io/Prosperitas-Arcana/

## Install on a phone or tablet
1. Open the address above in Safari (iPhone/iPad) or Chrome (Android).
2. iPhone/iPad: Share, then Add to Home Screen. Android: menu, then Install app.
3. Open it once while online. After that it also works offline.

## Playing on own devices (phones, tablets, PCs)
- The Master's iPad runs the table, can play a seat itself, and runs any bots.
- On the setup screen set each friend's seat to "Human, own device", then Start game. Everyone meets their House first (character card and ability card).
- On the table screen tap **Invite players** and send each friend their personal link (iMessage, WhatsApp, email).
- Friends open the link. They see their House, write orders and tap **Send my orders**. Orders reach the Master automatically, and each Year's result flows back automatically. No codes to paste.
- A friend can tap **Leave game** at any time. Their device is cleared and the Master is told. The Master then chooses **New invite link** (the old link stops working) or **Take over on this iPad**.
- If the live link ever fails, "Paste order code instead" and the backup game code still work.
- Live link: orders and results are relayed through the free public service ntfy.sh, using long random private topic names that exist only inside the invite links.
- Game data is stored on each device only. Use Master > Backup before clearing browser data.

## Releasing an update
Change `VERSION` in `sw.js`, upload the changed files, then open the app online twice.

Rules in this version: 12 Years in 4 Terms of 3, 50 Gold each, Holdings 9 Gold (Vesperis 7), each Holding counts as 3 of 6 actions, Debt Card then elimination, Debt cannot win.
