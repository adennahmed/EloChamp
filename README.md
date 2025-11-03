# EloChamp – Phase 1

## Overview

EloChamp Valorant is a zero-cost desktop overlay for Valorant players designed to deliver real-time performance stats and contextual coaching tips using Riot and Overwolf APIs. This MVP leverages Python (FastAPI) for backend processing, React+TypeScript for UI/overlay, and Supabase for free authentication and storage.

## Tech Stack

- **Frontend:** React, TypeScript, Overwolf SDK
- **Backend:** Python, FastAPI
- **Database:** Supabase (Postgres, Auth)
- **Infrastructure:** Overwolf for game event capture

## Planned Phase 1 Features

- Overlay activates during Valorant matches, presenting live performance stats.
- Python FastAPI backend receives game events and computes tips and tracking data.
- User game session and stat data stored/queryable via Supabase.
- Simple UI mockups provided.

## Usage Flow

1. User launches Valorant and EloChamp overlay (via Overwolf platform).
2. Overlay displays session K/D, accuracy, etc. (React UI).
3. Game events sent to backend—custom API endpoints written in Python/FastAPI.
4. User can view a post-game dashboard (planned in next phase).

See `prototype.md` for flow diagrams.
