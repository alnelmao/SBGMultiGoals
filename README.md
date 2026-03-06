# SBG MultiGoals

Team modes and custom game rules for **Super Battle Golf**.

## Features
- `Goals Required` slider (`1-100`) in the **MultiGoal** tab.
- `Score for each goal` toggle.
- `Points per goal` slider (`1-100`).
- `Game Mode` selector with `Standard`, `Team Chaos`, and `Team Competitive`.
- `Teams Count` slider (`2-4`).
- Host-controlled player-to-team assignment in lobby.
- `Competitive scoring mode`: `Simple (Decrement)`.
- Team scores and goal progress shown in TAB.
- Team tags in TAB name column: `[Team 1]`, `[Team 2]`, etc.
- Team-colored player names in TAB.
- Team-colored world name tags above player heads.
- Host-to-client mod sync for team assignments and goal counters.

## Scoring Summary
- `Standard`: default round flow + optional `Score for each goal` bonus.
- `Team Chaos`: goals are counted for the whole team.
- `Team Competitive`: each player finishes their own goal count, points are applied to team members according to mode rules.

## Recommended Match Settings
- For team modes, use `Player Speed = 200%`.
- For team modes, disable the game's standard bonus scoring.
- For `Team Competitive`, it is recommended to disable `Score for each goal`.

## Gameplay Ideas
- Different combinations of modes and options allow many play styles.
- In `Team Chaos`, part of the team can switch to attack/defense while the rest focus on scoring goals.
- Combine team modes with `Hit other player's balls` to turn matches into full chaos.

## Host And Client Requirements
- All mod logic works even if the mod is installed only on the host.
- Clients without the mod can still join and play with the host's active rules.
- For team info and goal counters in TAB (and other custom visuals), it is recommended that all players install the mod.

## Installation
- Place this package into the game folder so the DLL ends up at `BepInEx/plugins/SBGMultiGoals/SBGMultiGoals.dll`.

## Version
- `1.8.0`
