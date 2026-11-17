# weve-luanti

# WEVE: Western Engineering Virtual Explorer (Prototype)

SE 3351 Group 16: Alisha Patel, Simran Madahar, Raghad Hilwah

A Luanti world that recreates selected public areas of Western Engineering buildings. Visitors can explore the buildings, read information signs, and travel between buildings from a central spawn hub.

## What's included

Our group had three members instead of five, so the scope covers 2–3 approved areas in each building.

- **Amit Chakma Engineering Building (ACEB):** exterior with cantilevered entrance; level 1 north corridor, rooms 1400 and 1410, tiered lecture halls 1415 and 1420, and the double-height atrium with skylight; level 2; meeting room 3445 on level 3.
- **Spencer Engineering Building (SEB):** auditorium wing exterior and lecture halls 1200, 2200 and 2202.
- **Spawn hub:** Travelnet booths (network "WEVE") to travel between Spawn, ACEB and SEB, plus welcome and tour signs.
- **Information points:** signs at the main rooms with descriptions and a program link.
- **Not included:** Thompson Engineering Building (TEB), deferred to a later phase.

## Requirements

- [Luanti](https://www.luanti.org/downloads/) 5.17.0 or later (free; Windows, macOS, Linux)
- Minetest Game (installed from inside Luanti, see below)

The mods the world needs (WorldEdit, Travelnet, Xcompat and the spawn setup) are included in `weve_world/worldmods`.

## How to run

1. Install Luanti.
2. Open Luanti → **Content** → **Browse online content** → install **Minetest Game**.
3. Download this repository (**Code → Download ZIP**) and unzip it.
4. In Luanti, go to **About → Open User Data Directory**, open the `worlds` folder, and copy the `weve_world` folder into it.
5. Go to **Start Game**, select **weve_world**, tick **Creative Mode**, untick **Enable Damage**, and press **Play**.

You will start on the spawn hub.

## Controls

| Action | Key |
|---|---|
| Move | W A S D |
| Look | Mouse |
| Toggle fly | K (then Space / Shift to go up / down) |
| Read a sign or use a Travelnet booth | Right-click |
| Show coordinates | F5 |
| Return to the spawn hub | Type `/spawn` in chat (T) |

If flying doesn't work, open chat (T) and type `/grantme all`.

## Suggested tour

1. From the spawn hub, step into a Travelnet booth and choose **ACEB**.
2. Enter under the cantilever, walk the north corridor past rooms 1400 and 1410, and go into tiered hall 1415.
3. Continue to the atrium and look up through the skylight, then visit level 2.
4. Return with `/spawn`, take the booth to **SEB**, and enter lecture hall 1200.

## Notes

- The world is a prototype built from public Facilities floor plans. Mechanical rooms, stairs and other restricted spaces are shown as closed blocks.
- The original plan was a web-based experience. Luanti has no browser client, so the prototype is delivered as a downloadable world instead.
