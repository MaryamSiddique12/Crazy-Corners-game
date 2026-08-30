Corner Frenzy – Lobby update (keep all game rules the same)

WHAT CHANGED (only lobby)
- Host sees a live list of who joined (with names)
- Two clear buttons:
  1) "Start now (fill with AI)" – start even with 1–5 real players
  2) "Keep waiting" – stay in lobby for more friends
- When game starts, every real player appears with the name they typed
- AI fills remaining spots up to 6
- Levels, hunter, displacement, music, speed bar, controls = unchanged

HOW TO PLAY WITH FRIENDS
1. Both open the same website link (your Netlify link)
2. Host: type name → Create Room → Copy Code → send to friends
3. Friends: type name → paste code → Join
4. Host sees names appear in "Players in room"
5. Host: either wait, or tap "Start now (fill with AI)" → pick Level

UPDATE NETLIFY
1. Replace index.html with this file
2. git add .
3. git commit -m "Lobby: live player list + Start with AI button"
4. git push
5. Wait 1–2 min, hard-refresh on phones

NOTE
Room code is the PeerJS id (copy-paste). Both devices need internet.
