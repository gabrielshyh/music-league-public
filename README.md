<!-- Music League Public README -->
<!-- Formatted following marklovestech GitHub repository layout -->

<div align="center">

# Music League

**A full-stack social music competition platform featuring custom leagues, theme submissions, anonymous voting, and automated Spotify integration.**

[**🔗 Live Web App: musicleague.jgsms-ai.com**](https://musicleague.jgsms-ai.com/)

![frontend](https://img.shields.io/badge/frontend-React-blue)
![backend](https://img.shields.io/badge/backend-Fastify-black)
![cloud](https://img.shields.io/badge/cloud-AWS-orange)
![database](https://img.shields.io/badge/database-MySQL-orange)
![api](https://img.shields.io/badge/API-Spotify%20Web%20API-brightgreen)
![status](https://img.shields.io/badge/status-active%20development-yellow)

</div>

---

## What it does

Sharing and discovering music with friends should be competitive and engaging, but managing music leagues through group chats and spreadsheets is chaotic. Votes get miscounted, playlists take hours to compile, and tracking season standings becomes tedious.

Music League is a modern full-stack web application designed for competitive music sharing. Players join custom leagues, submit tracks matching weekly themes, vote anonymously on peer submissions with allocated point budgets, track real-time leaderboard rankings, and generate automated Spotify playlists with a single click.

Experience the live application at [musicleague.jgsms-ai.com](https://musicleague.jgsms-ai.com/).

## Highlights

- **Weekly Theme Competitions.** Create custom leagues with scheduled round themes, submission deadlines, and point allocation rules.
- **Anonymous Voting System.** Distribute point budgets across submitted tracks with comments to keep competition rounds fair and unbiased.
- **Automated Spotify Integration.** Searches Spotify's catalog, validates tracks, handles authentication, and automatically generates official round playlists.
- **Live Leaderboards & Standings.** Real-time season standings, round score breakdowns, and submission analytics.
- **Cloud Infrastructure.** Hosted on Amazon Web Services (AWS) with global CDN delivery, media storage, container compute, relational database management, and custom DNS routing.

## Architecture

Music League follows a decoupled client-server architecture designed for high responsiveness, secure authentication, and cloud scalability:

- **Frontend Interface:** A single-page application built with React, React Router, and Axios, providing interactive league management and real-time voting interfaces.
- **Backend API Server:** A lightweight, high-throughput Node.js server powered by Fastify, handling user sessions, Spotify OAuth token refresh, and complex point allocation logic.
- **Data & Media Layer:** Relational database storage powered by MySQL for user state, league rounds, and vote tabulations.
- **AWS Cloud Stack:** Deployed across AWS infrastructure including CloudFront (CDN distribution), S3 (static assets), Elastic Beanstalk (server compute), RDS (managed relational database), and Route 53 (DNS routing).

## Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React, React Router, Axios |
| **Backend** | Fastify, Node.js |
| **Database** | MySQL (Amazon RDS) |
| **Cloud Infrastructure** | AWS (CloudFront, S3, Elastic Beanstalk, RDS, Route 53) |
| **External APIs** | Spotify Web API |

## Status

**In active development now, beta version coming soon!**

## Why the source is private

This repo is a public-facing description of a working application. The full implementation lives in a private repository. If you are a collaborator, recruiter, or fellow builder who would like a deeper look into the codebase—please reach out below.

## Contact

**Gabriel Shyh** — [@gabrielshyh](https://github.com/gabrielshyh) · [gabrielsshyh2006@gmail.com](mailto:gabrielsshyh2006@gmail.com)