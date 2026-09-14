# Midgard

Pack version: `2026.09.14`

This is the public friends pack (`KemaneWright/valheim-pack`). Commit and push this repository. Friends' launchers pull the raw `manifest.json` URL. The manager/launcher source stays in the private `valheim-launcher` repo.

This does **not** update the dedicated server — use the manager **Sync to server** action for Docker BepInEx plugins/configs.

Do not run `pnpm server:sync` against the homelab container; that path copies a full game/BepInEx tree the image must not receive.

Packages: 34
Configs: 31
