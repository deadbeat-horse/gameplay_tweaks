### end goal
move the spyglass from the belt slot (as added by *spyglass improvements* via the *curios* API) to a custom spyglass accessory slot using *kubejs*

### current status
this repository currently contains only a datapack and resourcepack that are designed to isolate problems by running in a stripped-down environment
that has only *accessories* and its dependancies installed. in its current state, the slot is created and bound to the player with a quantity of 1,
the spyglass is added to that slot's tag and can be placed into the slot without issue, and from prior testing the spyglass *would* render at the hip
when placed in the slot if *spyglass improvements* were installed (which of course it isn't so this is irrelevant). the hurdles to overcome are the
slot not displaying the icon `gameplay_tweaks:gui/slot/spyglass` and a human-readable name for the slot not existing in the active lang file.

### status update
I've now overcome both hurdles described under [current status](#current-status). I've uploaded [the updated resource pack](corrected_resourcepack) to this repository for reference.

### version info
I am running `accessories-neoforge-1.1.0-beta.42+1.21.1` and `owo-lib-neoforge-0.12.15.1-beta.3+1.21` on neoforge 21.1.169 / minecraft 1.21.1 (duh).
