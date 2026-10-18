# Changelog

## 0.1.0 (2026-10-18)

First release: three Gazebo worlds for ArduPilot SITL, built from code (`tools/build.py`).

- **airfield**: grass field with a 400 m x 20 m east-west runway (centre line, edges, thresholds),
  taxiway, apron, hangar, windsock and trees.
- **mission_arena**: 1 km x 1 km area with boundary posts every 50 m, a landing pad, red and blue
  ground targets, a 7x7 marker board and three air-defence zones (transparent, visual only).
- **town**: 5 x 5 blocks with streets, buildings 6 to 30 m high and a central square with a pad.
- Every world loads the Gazebo systems ArduPilot needs and sits at ArduPilot's default location.
