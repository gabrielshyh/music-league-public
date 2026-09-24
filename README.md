<!-- Music League Public README -->
<!-- Formatted following marklovestech GitHub repository layout -->

<div align="center">

# Music League

**A full-stack social music competition platform featuring custom leagues, theme submissions, anonymous voting, and automated Spotify integration.**

![frontend](https://img.shields.io/badge/frontend-React%2019-blue)
![backend](https://img.shields.io/badge/backend-Fastify-black)
![database](https://img.shields.io/badge/database-MySQL-orange)
![api](https://img.shields.io/badge/API-Spotify%20Web%20API-brightgreen)
![status](https://img.shields.io/badge/status-actively%20maintained-brightgreen)

</div>

---

## What it does

Sharing and discovering music with friends should be competitive and engaging, but managing music leagues through group chats and spreadsheets is chaotic. Votes get miscounted, playlists take hours to compile, and tracking season standings becomes tedious.

Music League is a modern full-stack web application designed for competitive music sharing. Players join custom leagues, submit tracks matching weekly themes, vote anonymously on peer submissions with allocated point budgets, track real-time leaderboard rankings, and generate automated Spotify playlists with a single click.

## Highlights

- **Weekly Theme Competitions.** Create custom leagues with scheduled round themes, submission deadlines, and point allocation rules.
- **Anonymous Voting System.** Distribute point budgets across submitted tracks with comments to keep competition rounds fair and unbiased.
- **Automated Spotify Integration.** Searches Spotify's catalog, validates track URIs, manages OAuth token refresh, and automatically generates official round playlists.
- **Live Leaderboards & Standings.** Real-time season standings, round score breakdowns, and historical submission analytics.

## Unique Feature: Automated Spotify OAuth Sync & Voting Engine

Managing round playlists and scoring by hand is completely eliminated:

- **Instant Playlist Generation:** Upon submission deadline, the backend automatically resolves Spotify track URIs, authenticates via OAuth 2.0 refresh tokens, and generates an official Spotify playlist for the league round.
- **Strict Point Allocation Engine:** Fastify endpoints evaluate anonymous voting rules, enforcing point budget constraints and calculating live cumulative season leaderboards in MySQL.

## Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React 19, Vite, React Router v7, Axios, Day.js |
| **Backend** | Fastify, Node.js, `@fastify/cors`, `@fastify/mysql` |
| **Database** | MySQL |
| **External APIs** | Spotify Web API (OAuth 2.0, Catalog Search, Playlist Management) |

## Why the source is private

This repo is a public-facing description of a working application. The full implementation lives in a private repository. If you are a collaborator, recruiter, or fellow builder who would like a deeper look into the codebase—please reach out below.

## Contact

**Gabriel Shyh** — [@gabrielshyh](https://github.com/gabrielshyh) · [gabrielsshyh2006@gmail.com](mailto:gabrielsshyh2006@gmail.com)