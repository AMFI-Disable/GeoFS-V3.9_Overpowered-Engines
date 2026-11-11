# Changelog

All notable changes, propulsion scaling enhancements, and version releases for GeoFS-V3.9 Overpowered Engines are documented in this file.

---

## [3.9.0] - Unified Metadata

### Changed

- Standardize the userscript metadata and version across the V3.9 ecosystem.
- Match only the GeoFS main site and activate only when it reports V3.9.

---

## [Unreleased]

### Changed

- **Theme Alignment**: Updated propulsion control panel headers, keybind buttons, and active states for thrust, ceiling, and SAS toggles to neutral `#dddddd` and green `#4caf50`.
- **Favicon Metadata**: Switched userscript icon reference to the official GeoFS favicon.

---

## [2.0.8] - GeoFS V3.9 Compatibility

### Changed

- Start only after GeoFS reports V3.9; remain inactive on other or unrecognized versions.
- Update compatibility documentation and version metadata.

---

## [2.0.2] - Stability Augmentation And Hypersonic Ceilings

### Added

- **Stability Augmentation System (SAS)**: Real-time stabilization loop to damp out asymmetric torque and aerodynamic departure at hypersonic velocities.
- **Hypersonic Atmospheric Ceiling**: Extends simulation limits up to sub-orbital operational ceilings.

### Fixed

- **Afterburner Flame Shaders**: Fixed visual flame effects clipping into aircraft exhaust nozzles at extreme thrust multipliers.
- **Thrust Step Responsiveness**: Smoothed acceleration curves when scaling beyond standard engine thrust limits.

---

## [2.0.0] - Dual-Core Propulsion Engine

### Added

- **Dual-Core Physics Engine**: Independent multiplier controls for Engine Thrust (up to 100,000x) and Atmospheric Ceiling.
- **Glassmorphic Propulsion Panel**: Touch-friendly slider interface for real-time thrust tuning.

---

## [1.0.0] - Initial Production Release

Initial release of the propulsion multiplier and engine scaling framework for GeoFS.
