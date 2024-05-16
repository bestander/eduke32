# Eduke32 fork to allow rendering on a LED matrix

This is a fork of https://voidpoint.io/terminx/eduke32.

With the following additions (see latest commits by @bestander) that make https://github.com/bestander/duke3d-matrix work:
- Added callbacks to SDL rendering behind SDL_OVERRIDE_RENDERING macro
- Added input commands Random_Level (switch to a random level) and Get_Stuff (get all weapons, medkit and jetpack) to make the game playable from a gamepad
- Fixes crash caused by some gamepads