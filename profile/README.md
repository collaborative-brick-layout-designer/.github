# Brick Layout Designer

Open-source tools for designing LEGO train layouts — from solo planning to real-time club collaboration.

---

## Projects

### [brick-layout-designer](https://github.com/brick-layout-designer/brick-layout-designer)
A cross-platform maintainer fork of **[BlueBrick](https://github.com/Lswbanban/BlueBrick)**, rewritten in C++20 / Qt 6.
Runs natively on Windows, Linux, and macOS (Intel + Apple Silicon) with no .NET / Mono dependency.
Reads and writes `.bbm` files byte-faithfully so projects move freely between this tool and vanilla BlueBrick.

**Highlights**
- Cross-layer modules — bundle bricks across layers into a named unit; move, rotate, and save as standalone `.bbm`
- Anchored text labels — labels follow their bricks when moved or rotated
- Event venues — model the physical space (walls, doors, obstacles, walkway buffers) with live validation
- LDraw / Studio / LDD import → top-down sprite, snap-compatible with existing track parts
- CI/CD releasing signed installers for all four platforms on every tag

### [collaborative-brick-layout-designer](https://github.com/brick-layout-designer/collaborative-brick-layout-designer)
A real-time multi-user web editor for LEGO-style brick layouts.
Self-hosted via Docker — bring your own server, own your data.

---

## Relationship to BlueBrick

Both projects stand on the shoulders of **[BlueBrick](https://github.com/Lswbanban/BlueBrick)** and the **[BlueBrickParts](https://github.com/Lswbanban/BlueBrickParts)** community library.
The file format, parts library, connection-snap model, and layer system all trace directly back to BlueBrick's design.
If you need the mature, battle-tested tool — use BlueBrick.
If you want cross-platform native binaries or real-time collaboration — you're in the right place.

**Please go star the original [BlueBrick](https://github.com/Lswbanban/BlueBrick) and [BlueBrickParts](https://github.com/Lswbanban/BlueBrickParts) repos.** They are the foundation.
