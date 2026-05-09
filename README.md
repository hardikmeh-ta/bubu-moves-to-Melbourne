# Amanda's Melbourne Move Planner 🌏

A personal relocation planning app for the Chicago → Melbourne move.

## Features
- **Checklist** — 40+ pre-loaded tasks across 8 timeline phases (based on Jul 29 flight)
- **Inventory manager** — add items to sell/donate/bin, with photo upload and notes
- **Sell task automation** — adding a "Sell" item auto-creates a checklist task with deadlines and platform recommendations
- **Calendar export** — add individual tasks or all remaining tasks to Google Calendar or Apple Calendar (ICS)
- **Role toggle** — "Amanda mode" to check off tasks and edit notes; "View only" for Hardik
- **Shared data** — Supabase backend, syncs across both devices in real-time

## Setup

1. Clone the repo
2. Enable GitHub Pages: Settings → Pages → Source: Deploy from branch `main`, folder `/root`
3. Done — the app is live at `https://[your-username].github.io/[repo-name]`

## Usage

- **Amanda** — open the link, tap "View only" in the top right to switch to "Amanda mode"
- **Hardik** — stays in view-only mode by default on his device

## Stack
- React 18 (CDN)
- Supabase (database + file storage)
- Tabler Icons
- GitHub Pages (static hosting)

## Supabase Schema
See SQL in the project setup notes.
