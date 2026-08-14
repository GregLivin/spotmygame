# SpotMyGame

SpotMyGame is a sports recruiting platform for basketball and football athletes of all ages. Instead of asking athletes to self-upload phone footage and hope a coach finds them, a real media team attends games, films standout plays, and edits a professional highlight reel — **for free**. Athletes claim their content by creating a free account, which becomes their public recruiting profile.

## Live demo

This repo contains a self-contained prototype (`index.html`) with no build step or dependencies. Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` → `/root`), it will be live at:

`https://greglivin.github.io/spotmygame/`

You can also just open `index.html` directly in any browser.

## What's in the prototype

- **Home** — the core pitch and calls to action
- **How It Works** — the six-step loop from game day to getting discovered
- **Get Filmed** — a request-coverage form for athletes, parents, or coaches to ask the media team to attend a game
- **For Athletes** / **For Coaches** — value-prop pages for each audience
- **Scout Talent** — an open, no-account-required search of sample athlete profiles, filterable by state, city, school, sport, and grad year
- **Awards & Spotlight** — sample "Player of the Week" recognition cards
- **Sign Up** — a COPPA-aware account creation flow: it calculates age from date of birth and, for athletes under 13, requires parent/guardian details plus two required consent checkboxes (guardian confirmation + data-collection consent) and one **separate, optional** checkbox specifically for promotional/social media use. Athletes 13+ get a simpler single-consent flow.

**This is a prototype only.** No real accounts, videos, or personal data are collected or stored — all state lives in the browser and resets on refresh. See the in-page footer for what a production build would still need (verifiable parental consent, a published data-retention policy, signed media releases).

## Tech

Plain HTML, CSS, and vanilla JavaScript in a single file. No frameworks, no build tooling, no external network calls — works fully offline and deploys as-is to GitHub Pages.

## Legal notes (read before going beyond prototype)

- **COPPA** applies to any collection of personal info — including photos/video — from users under 13. It requires verifiable parental consent, minimal data collection, a clear privacy policy, and (as of the 2026 rule update) *separate* consent for data collection vs. sharing/promotional use.
- **Filming and using a minor's likeness for promotion** generally requires written parental consent regardless of state, even when filmed in a public setting like a school game.
- Consult an attorney before collecting real user data or publishing real footage of minors.

## Roadmap

See the project brainstorm doc (shared separately) for the fuller feature roadmap, monetization models, and open operational questions (launch geography, sport/age priority, media team logistics).
