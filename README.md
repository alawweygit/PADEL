# Padel

A live, shareable scoreboard for padel sessions — rotating 2v2 doubles where partners change each round so individual points accumulate fairly across the group.

## Features
- Enter 4–10 players, auto-calculates minimum rounds needed for everyone to partner with everyone
- Mark players as "running late" to skip them in early rounds
- Generates a fair rotation (minimizes repeated partners/opponents)
- Add unlimited extra rounds on the fly, generated fairly based on match history
- Shareable link — anyone who opens it sees the same live leaderboard and can tap in results
- No backend setup required (uses jsonblob.com as a free shared state store)

## Deploy
Static site, no build step. Import this repo into Vercel and deploy as-is.

## Usage
1. Open the deployed link
2. Enter session name + player names (one per line)
3. Tap any late arrivals
4. Hit "Generate Schedule & Get Link"
5. Share the resulting link with your group — everyone can tap in winners live
