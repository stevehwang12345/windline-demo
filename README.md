# WINDLINE 1.3.1

Full public web release of the WINDLINE sailing game (version 1.3.1, rules m13.0). The existing URL is retained so earlier links keep working.

[Play WINDLINE](https://stevehwang12345.github.io/windline-demo/)

New in 1.3.1: more forgiving mobile controls. Direction buttons are 60px tall and tolerate 12px of thumb drift. Moving farther away stops the action; moving back resumes it, and sliding onto the neighboring button changes direction. Release, cancellation, rotation and loss of focus clear the contact. Steering and sail trim remain independent.

New in 1.3.0: three instrumental music tracks supplied by the creator. Harbor at Dawn accompanies the title and recovery passages, Windward Horizon accompanies ordinary sailing, and The Turning Tide accompanies challenges and active pirate pursuits. Music loops, crossfades between roles and resumes its previous position. The music-note button controls music and effects together; mute persists across title/restart within the page. Playback begins after interaction and pauses with the game or when the page loses focus.

New in 1.2.0: level-based navigation difficulty. Later passages require wider turns: up to 95 degrees at levels 7–10, 130 degrees at levels 12–20, and 165 degrees from level 22 onward. Recovery passages use gentle turns. More validated reef positions and tighter outer spacing make later routes more demanding; actual reef counts depend on available space. The opening passage and safe navigation clearances are preserved.

New in 1.1.1: more varied harbor-to-harbor distances. Consecutive passages prefer a different length while preserving safe arrival, short recovery passages and the original opening. The remaining-distance readout measures the distance to the harbor entry circle, not the center of the island.

New in 1.1.0: random mermaid, whale and pirate encounters with their own artwork, warning cues and rewards. From passage two, up to one encounter may appear per passage. The opening and recovery passages stay quiet.

- Approach a mermaid within 14 metres for one second to repair the hull, gain a five-second speed boost and earn encounter points.
- Watch the three-second splash warning and steer clear of a crossing whale. A collision damages and slows the ship once.
- Pirates pursue from behind. Escape by sailing well, putting reefs in their way, surviving the pursuit or reaching the harbor.

Encounter bonuses appear in the arrival score breakdown. Pause freezes encounters, and the music-note button mutes their effects too. Earlier route obstacles, headwind handling, upgrades and sailing sounds remain available.

Headwind: reduce canvas to REEF and align the sail with the trim guide. Sailing at an angle and tacking remains faster than heading straight into the wind. Use the music-note button to switch wind and sound effects on/off.

Desktop: A/D or arrows to steer, Q/E for sail angle, Space for sail area.

Phone: hold the left arrow buttons to steer, hold the right minus/plus buttons for sail angle, and tap the center button for sail area. Steering and sail angle support simultaneous touches. Both portrait and landscape are supported.

The title screen includes an optional support dialog with the creator's bank details and an account-number copy button.

Original source, design documents and tests are maintained in a private repository. This repository contains only the public runtime build and bundled font notices. Older hashed assets remain available for existing cached pages.
