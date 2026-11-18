# GTA 6 cheat codes data

`cheats.json` is the live cheat list for the VI Cheats app (unofficial, fan-made).
The app downloads it from:

https://raw.githubusercontent.com/nirmalparmar/gta-cheat-codes/main/cheats.json

## Adding a newly published code

1. Edit `cheats.json` and fill in the `code` for the cheat (space-separated:
   `U D L R` for the D-pad).
2. Increase `version` by 1 and set `updated` to today's date.
3. Commit and push to `main`.

Phones pick it up on next launch or when the user pulls down on the home screen.
Keep every `id` unchanged; favorites are stored by id.

Sources: PC Gamer and Red Bull GTA 6 cheat guides. Not affiliated with Rockstar Games or Take-Two Interactive.
