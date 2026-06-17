# pokemon-rb-spite
An extremely minimally edited apworld of Alchav's Pokemon Red/Blue implementation reverting Poke Doll and Bicycle logical-breaks to vanilla behavior.

This should completely function client-side, meaning that you won't need to send this to the multworld host in order to enjoy the fix.

This is an extremely trivial change!  Compared to Alchav's "Version 6, Beta 6" released in January, there is exactly 6 lines altered, and that's just commenting out lines 393-396 and 398-402 in rom.py.

The result of this is allowing for the Poke Doll skip in Lavender Tower as well as allowing the player to get onto Cycling Road without a Bicycle, while not expecting the player to do either within the randomizer logic.

The modification is solely clientside and solely in the patching process, meaning that only games patched with this apworld will be affected.  Meaning that it should have 100% compatibility with Alchav's actual beta apworld, and will only affect players who have my apworld installed, regardless if the game was generated with my apworld.

# IF YOU USE THIS APWORLD AT ALL, DO NOT REPORT BUGS TO ALCHAV AS THIS UNOFFICIAL VERSION IS NOT WITHIN HIS DEVELOPMENT SCOPE

This is not a fork for competition or cooperation, I consider this a modification for personal use and any comparison to Alchav's project is incredibly obvious and circumstantial.  I do not intend on keeping up with feature updates from Alchav.

If you want to see more impactful changes and development, please follow his project pages/repos.  However, he has gone on record multiple times with his intentions to not allow for this specific change to be part of his apworld.
https://github.com/ArchipelagoMW/Archipelago/pull/5126

I intend on "upkeeping" with Archipelago's changes, so long as the required changes are minimal in scope, as I do not currently have the knowledge or want to restructure anything.
