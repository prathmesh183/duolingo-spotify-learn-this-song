# Duolingo × Spotify: "Learn This Song"

**Product case study (PRD, strategy deck, clickable prototype)**  
Author: Prathmesh Sakore

Turn the songs people already stream on Spotify into 2-minute Duolingo lessons.

**Live prototype:** _add your GitHub Pages link here_

## The problem
Millions of people stream songs in Spanish, Korean or French without understanding the lyrics, and opening a separate app just to "study" is the first habit people drop.

## The idea
A "Learn this song" chip on Spotify's lyrics view hands off to a short Duolingo lesson built from that song's lyrics. Finishing the lesson earns XP, extends the streak, and unlocks a "Song Unlocked" badge back on Spotify.

## Key product decisions
| Decision | Choice |
|---|---|
| Prioritization | RICE: Spotify in-app widget scores highest (135) and is P0 |
| North-star metric | CTA → lesson completion rate above 25% |
| Guardrails | Spotify session length drop no more than 2%; lesson quality complaints under 1% |
| Pilot | Single market and language first (e.g. Korean in South Korea) |
| v1 excludes | Full translation, pronunciation scoring, languages outside the top 5 |

## What's in this repo
- `docs/` – PRD and strategy deck
- `index.html` – clickable prototype (open it in a browser)

## About the prototype
Front-end only. Songs and lyrics are fictional, audio is a synthesized tone, and there are no real Spotify or Duolingo APIs. It demonstrates:
- Eligibility by persona (no account, lapsed learner, active streaker)
- CEFR level filtering of songs
- Deep link handoff and web fallback
- Micro-lesson, reward loop, and a funnel tracker
