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

## New in this version
- **Sounds** for every action, including orders arriving from other devices, Year changes and the winner.
- **Year report** for each player after every Year: gold change, what your House did, and standings.
- **Winner ceremony** after Year 12 (Skip / Replay available).
- **Screen stays awake** while the app is open (iOS 16.4+ and modern Android). It reconnects automatically after the phone wakes.
- **Contested Holdings:** if two or more players try to buy the same Holding in a Year, nobody buys it and it stays available (as in the rulebook).

Update: open the app online twice on each device so the new version is cached.

## New in v5
- **Living House cards:** the character art now breathes and shimmers, with a per-House effect (Astravan stars, Aurivane golden sparks, Corvenis orbiting lights, Caelorum rising embers and lanterns, Vesperis orbiting crystals). Used in the House reveal and on the winner's card.
- **Master-run finale:** in the final Year the Master screen plays the resolution with all Gold numbers hidden ("???"). The phones are told nothing until the Master presses **Begin the ceremony**. Then every screen runs the build-up from last place to first, a drum roll, and the winner reveal with fireworks.
- Phones can open **My Year 12 report** after the ceremony. The Master can use **Resend result to phones** if a device missed it.

## New in v7: phone-friendly order sheet
- The order sheet now opens on a **menu of buttons**: Manufactured Goods & Market Movers, Refined & Processed Materials, Trade Sell, Trade Buy, Raw Materials, Holdings, My Stock, Opponent Stock, House, Rule Book. Buttons are dimmed (but still open) when you cannot act in that category, and a gold badge shows how many orders you have placed there.
- Each category opens a **full-screen card page**: one big card at a time, with the quantity selector beneath it. Swipe sideways (or use the arrows or the thumbnail strip) to move through the cards. Cards you cannot use are grey.
- **Contracts:** a one-tap "Bid X Gold (recommended)" button, and the bid pull-down starts at the recommended value. The Market Mover card is the first card in the Manufactured Goods page.
- The **complete rulebook** is in the Rule Book section.
- The phone's Back button returns from a page to the menu.
- Card pictures are now sharper (the app file is larger, about 3.5 MB). Open it online twice on each device to refresh.

## New in v8
- Cards stay in full colour even when you cannot use them, so you can still read the colour and sigil recipe. An unavailable card has a greyed quantity pull-down that says why ("Unavailable: needs Arcanite + Aether"). Menu buttons still dim.
- The **version number** (currently Version 8, 21 Nov 2026) is shown on the setup page, the join page, the seat page, the House reveal and the order menu. Everyone should see the same number.

## New in v9
- All Manufactured Goods Max values are 10 lower (50 and 40 instead of 60 and 50). The in-app rulebook is updated to match.
- After sending orders, a player can open the **Rule Book** and **Opponent Stock** from the order-sent screen.
- **Order timer:** the Master picks the time at setup (No timer, or 30 to 300 seconds in 30-second steps). It starts when the Master starts the Year, with a 30-second alarm. When it runs out, each player's selected orders are sent automatically. If their selection is invalid, an invalid part is dropped. A player on the Master device has their open sheet locked in. The Master can press **Restart timer** during a Year.

## New in v10
- When the timer runs out, every player's order is issued **exactly as selected** (including an edit in progress), and the order is then **final**: the "Change my orders" button disappears.
- The only part dropped is a Holding purchase while the player still has Debt that is not being repaid. Any single action that breaks the rules is also dropped, and everything else is kept.
