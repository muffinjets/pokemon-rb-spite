# pokemon-rb-spite
An extremely minimally edited apworld of Alchav's Pokemon Red/Blue implementation reverting presumptious patches that affect the vanilla experience.

This modification completely functions client-side, meaning that you won't need to send this to the multworld host in order to enjoy the fix.  Just replace the existing .apworld in your Archipelago installation, and everything else should work seamlessly.

The following versions are supported as of 24 June, 2026:
 - Version 7, Beta 1 ("The update that adds Yellow")
 - Archipelago 0.6.7 ("Core-verified")

(If you don't know which to pick, and you didn't even know Yellow was playable, choose the "core" version)

No matter which you pick, RENAME THE APWORLD to remove the all-caps "_VXBETAX" or "_CORE" before you install.


## WHY DOES THIS EXIST?
The .apworld that comes shipped with Archipelago makes the following changes to the base Red/Blue/Yellow experience:
 - Using a Poke Doll on the ghost Marowak encounter at the top of Pokemon Tower is patched out, it is, by default, not possible to advance through the Pokemon Tower without the Silph Scope item.
 - The guard at Route 16's Gate was skippable if the player didn't have the bicycle by simply persistently attempting to walk through.  This was also fixed, and made impossible to pass without the Bicycle.
 - Invisible items were made impossible to pick up without the Itemfinder.

All of these "fixes" are made into options, but when the patches are disabled, the player may now be required to learns these skips and glitches in order to progress via the Archipelago randomizer's logic.  I have reverted all of these issues, while keeping the entire rest of the apworld files untouched.  The result, now when the player enables the patches, they simply won't patch, allowing the player to perform these tricks to gain out-of-logic progression in their Archipelago games.

## TO PUT IT ANOTHER WAY, HERE'S WHAT I CHANGED:
 - Using a Poke Doll on the ghost Marowak encounter is now possible, no matter what.
    - If the player chooses "Patched" in the yaml, that knowledge will not be expected for the player to know.
 - The guard at Route 16's Gate can be skipped by persistently attempting to move past his trigger.
    - If the player chooses "Patched" in their yaml file, that knowledge will not be expected for the player to know.
 - Invisible items are now able to be picked up without the itemfinder.
    - If the player selects "Require Itemfinder" in their yaml, hidden items will logically expect the Itemfinder.

All of these changes can and should be audited!  The only script I have altered from Alchav's repo is rom.py, in which I simply commented out the lines that declare how the patcher should act when the player "chooses" to patch out these tricks.

# IF YOU USE THIS APWORLD AT ALL, DO NOT REPORT BUGS TO ALCHAV AS THIS UNOFFICIAL VERSION IS NOT WITHIN HIS DEVELOPMENT SCOPE

This is not a fork for competition or cooperation, I consider this a modification for personal use and any comparison to Alchav's project is incredibly obvious and circumstantial.  I only intend to keep up to date with the upstream repository, so long as the means of which my reversions work continue to be simple to understand.  This also applies with Archipelago's core.  I am not a world developer, I just know how to unzip an .apworld.  I highly encourage people to take after me if they so wish.

If you want to see more impactful changes and development, please follow his project pages/repos.  However, he has gone on record multiple times with his intentions to not allow for this specific change to be part of his apworld.
https://github.com/ArchipelagoMW/Archipelago/pull/5126
