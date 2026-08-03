# All-Star Team-Up 2K Arena

Private 5v5 NBA 2K tournaments — real NBA All-Stars only, Hall of Fame difficulty, real cash prizes.

🌐 **Live site:** https://allstarteamup2k26-cyber.github.io/ASTU_2K_ARENA-/
💬 **Discord:** https://discord.gg/vWE3Qk5HhE
📸 **Social:** [@all_star_team_up](https://instagram.com/all_star_team_up)

---

## What is All-Star Team-Up?

All-Star Team-Up is a private 5v5 NBA 2K game mode. One player creates a private locker room and invites 9 others (10 total). The host sets the lobby to **East vs West**, **Hall of Fame** difficulty, and **5-minute quarters**. Every player then picks a position and a real NBA All-Star — any era, old school to new school. Then it's tip-off.

This site runs that mode as a bracketed tournament series with real cash prizes.

## Season 1 Tournaments (7 total)

| Game | Platform |
|---|---|
| NBA 2K26 | PS5 |
| NBA 2K26 | PS4 |
| NBA 2K26 | Xbox Series X\|S |
| NBA 2K26 | Xbox One |
| NBA 2K25 | PS5 & PS4 |
| NBA 2K25 | Xbox Series X\|S |
| NBA 2K25 | Xbox One |

**Format:** 8 teams minimum / 16 max per tournament · Round Robin group stage → Double Elimination bracket
**Entry:** $50 per team (5 players) or $15 solo (auto-assigned to a balanced team)
**Prizes:** $300 / $100 / $50 per tournament ($450 total)

## Site Structure

```
index.html                          — homepage, links to all 7 tournaments
nba2k26-ps5-tournament.html         — NBA 2K26 PS5
nba2k26-ps4-tournament.html         — NBA 2K26 PS4
nba2k25-tournament.html             — NBA 2K25 PS5 & PS4
nba2k26-xboxseries-tournament.html  — NBA 2K26 Xbox Series X|S
nba2k26-xboxone-tournament.html     — NBA 2K26 Xbox One
nba2k25-xboxseries-tournament.html  — NBA 2K25 Xbox Series X|S
nba2k25-xboxone-tournament.html     — NBA 2K25 Xbox One
register.html                       — central registration form (all 7 tournaments)
admin.html                          — password-gated admin panel (rosters, teams, brackets)
find-players.html                   — public Look for Players board
logo.png                            — site logo
```

## Backend

Registration, the Look for Players board, and admin data are powered by a small Express API hosted on Replit. See that project for backend source and setup.

## Tech

Plain HTML/CSS/JS, no build step. Deployed via GitHub Pages (branch: `main`, root).
