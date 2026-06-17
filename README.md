# pokemon-rb-spite
An extremely minimally edited apworld of Alchav's Pokemon Red/Blue implementation reverting Poke Doll and Bicycle logical-breaks to vanilla behavior.

This should completely function client-side, meaning that you won't need to send this to the multworld host in order to enjoy the fix.

This is an extremely trivial change!  Compared to Alchav's "Version 6, Beta 6" released in January, there is exactly 6 lines altered, and that's just commenting out lines 393-396 and 398-402 in rom.py.

This does mean that when the user selects the "patched" option within the settings-choice yaml, it simply won't apply the patch that prevents it from happening, meaning that it's now possible to perform these skips while not being expected to do such logically.
