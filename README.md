# No Hurtcam for Horizon

Native Horizon mod port of the PvP pack's No Hurtcam feature.

It sets Horizon's `damageTiltStrength` argument to zero when building the camera bob matrix. This removes the camera roll caused by damage while preserving walking bobbing and the death camera effect.

## Compatibility

- Horizon Minecraft 26.3
- Pinned Horizon revision: see `horizon-native.json`
- Requires a native-mod build from the Horizon launcher. Java/Fabric `.jar` files are not used.

## Install from GitHub

In Horizon's launcher, open **Mods → Add from GitHub** and paste:

`https://github.com/rivatc160-png/horizon-no-hurtcam`

Select `no_hurtcam`, review and accept Horizon's native-code warning, then build it from **Settings → Native mods**. Horizon builds this source on its pinned game revision; the mod may need an update for a later Horizon revision.

## Validation status

The package and injection metadata were prepared against the pinned source. A Rust/Cargo build could not be run in this environment because Cargo is unavailable, so compilation in the Horizon launcher remains to be confirmed.
