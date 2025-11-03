# EloChamp Valorant – Prototype UX Flow

## 1. Overlay Launch
- Overwolf triggers overlay on Valorant match start.
- Display K/D ratio, accuracy, headshot %, and post-game dashboard button.

## 2. Game Events API Capture
- User plays Valorant, overlay receives live game events.
- Backend (Python + FastAPI) processes events, stores in Supabase.

## 3. Coaching Tips
- Python rules engine analyzes performance, sends contextual tips (crosshair, positioning) to overlay.

## 4. Post-Game Dashboard
- After match, user views round-by-round stats, economy/utility usage.
- Visualizations via Recharts in React dashboard.

## 5. Social Features & Highlights (Later MVP)
- Automated highlight clips (backend/Python, FFmpeg) and leaderboards.
- Sharing options (TikTok, Discord, mobile companion via React Native).

---
