# Changelog

## v1.2.0

### Added

- Added support for placing fish feed while active Fishing Rods remain in place.
- Added the `ded` dead-fish reaction alongside the existing death reactions.

### Improved

- Removed the fixed Fishing Rod limit while keeping simultaneous rods independent.
- Improved cumulative overfeeding and Severe Overfeeding behavior so repeated feeding increases risk over time.
- Increased health deterioration for Overfed, Severely overfed, Weak, and Critical fish.
- Improved fishing and feeding interaction consistency for hook-committed fish.
- Refined Guppy sizing.

### Fixed

- Fixed cases where severely overfed fish could remain healthy for too long.
- Fixed conflicts between feeding and active Fishing Rods.
- Fixed hooked or hook-committed fish being eligible to chase feed.

## v1.1.0

- Added fish health, hunger, and feeding status
- Added Fishing Rod interactions with multiple active casts
- Added shark, whale, and stingray fish
- Expanded fish naming, reactions, bubbles, and behavior
- Improved aquarium controls, multi-monitor behavior, and user interface
- Added self-contained installer and portable Windows packages
