# Roadmap

Leonida Life is pre-release: nothing below is publicly released yet, and there are no dates. This list moves only when work actually lands. It never lists something as available before you can run it.

## Implemented
In the codebase and tested, not released yet.
- Server core: a single self-hosted Go service with PostgreSQL
- Administrator accounts, sessions and audit log
- World configuration: one versioned document, validation with precise errors, draft, publish and rollback
- Classic Life world template on an original map (no game assets)
- Dynamic commodity market engine: supply and demand pricing, recovery, spread, bounded noise
- Public market demo and a market simulation tool to balance economies before players arrive
- Gameplay runtime: characters, inventory, money ledger, licenses, shops, gathering, processing, interactions, session resets
- Admin studio with the visual world and map editor and a guided supply-chain builder
- Website, early-access waitlist and launch notifications (live at leonidalife.dev)
- Docker packaging for self-hosting
- Vehicles, garages, impound and shareable keys (temporary and permanent)
- Factions with ranks, permissions and salaries; temporary groups; persistent organizations with shared bank, vault and vehicles
- Player-to-player interactions, trades, configurable justice (fines, wanted levels, records, prison), death and respawn

## In development
Being built now, not merged yet.
- Browser simulator to play-test a world without any game
- In-game UI kit and phone: inventory, shops, bank, market app

## Planned
Designed, not started.
- FiveM adapter as a proof of concept
- More templates beyond Classic Life
- Bank heists for rebel factions

## Blocked by external SDK
- GTA VI adapter. Rockstar Games has not released official multiplayer or modding tools for GTA VI. Until it does, nobody can run a Leonida Life server inside GTA VI, and we will not ship workarounds. The core is game-independent so it is ready when official tools exist.
