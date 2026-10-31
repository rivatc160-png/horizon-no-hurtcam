# No Hurtcam for Horizon

Native Horizon mod port of the PvP pack's No Hurtcam feature.

It sets Horizon's `damageTiltStrength` argument to zero when building the camera bob matrix. This removes the camera roll caused by damage while preserving walking bobbing and the death camera effect.

## Compatibility

- Horizon Minecraft 26.3
- Pinned Horizon revision: see `horizon-native.json`
- Requires a native-mod build from the Horizon launcher. Java/Fabric `.jar` files are not used.

## Install

Install `no-hurtcam-0.1.0.hnmod` through Horizon's native mod flow. Native mods run as compiled game code and Horizon displays its normal trust/build warning. This mod is tied to the pinned Horizon revision; another Nightly may require a rebuild against its matching source.

## Validation status

The package and injection metadata were prepared against the pinned source. A Rust/Cargo build could not be run in this environment because Cargo is unavailable, so compilation in the Horizon launcher remains to be confirmed.
