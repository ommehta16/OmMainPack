*Changelog:*
 - Made pack
**1.0.1 and before:**
 - Better enchantment glint on many many items(similar to Java, not pixel-by pixel on item)
 - UI with settings on main column and achievments in profile
 - Lower/Smaller Shield
 - Smaller totem
 - Better 3rd person off-hand shield raise animation
 - Transparent Pumpkin Blur
 - Transparent Spyglass overlay
**1.0.2:**
 - Closer to Java trident hit animation(not perfect, because I have nooooooo idea how sin functions work)
 - Messed around with first person hit animations - didn't go anywhere tho
 - Deleted some code for VR(since I can't even use it, and it just ends up making a mess of the code)
 - Made the README file
**1.0.3:**
 - Made a new hit animation, used by:
    - Bows
    - Tridents
    - Spyglass
 - Made a new shield hit animation
 - Altered the Crossbow hit animation
 - Made the shield visually re-equip when your main hand item re-equips
 - Deleted some code for VR
 - formatted the code in player_firstperson.animation.json
**1.0.4:**
 - Fixed an issue where when raising a trident while in riptide, the trident would not visually raise
 - Formatted all JSONs yet to be formatted
**1.0.5:**
 - Made new hit animation more broad, that way as more items become data-driven, I don't have to do as much manual fixing
**1.0.6:**
 - Fixed bugs with z-fighting caused by changed shield model
 KNOWN BUG: cubes in handle of shield show through the shield
 POSSIBLE FIX: making handle cubes within a seperate group - Note: this will probably break the item when dropped, but expirement w/ this in future
**1.0.7:**
 - Made all data-driven items(except for trident, spyglass and empty hand) use a new attack animation that I found in the default pack files that more closely resembles what the hit animation should be for them. The trident, and spyglass share a hit animation (since they're essentially just 2 long sticks and don't work well with default hit animation). The hand needs a special one since its special
 - Updated formatting on shield model to v1.16, instead of v1.8
**1.0.8:**
 - Slightly changed first person hit animation when holding nothing
 - Added a WIP piece of code to make the leftarm appear to pull back the bow string(currently I made the checks use to find what item is being held to read 'bowWIP', instead of 'bow', so change that when editing in future)
**1.0.9:**
 - Made crossbow appear in middle of screen when fully charged
 - Made left arm appear to hold bow when pulling it back(instead of actually pulling it back, since that was much big annoy)
**1.1.0:**
 - yeeted left arm holding bow(was being big annoy)
 - Changed hit animation once again
 - Made spyglass appear properly in first person(again)
 - Fixed bow vibration bug
 - Fixed trident not visually pulling back while in riptide(again.)
 - Made it so that some data-driven items change their position while in riptide
 - Changed the icon for equipment to be nicer
 - Changed the hit animation while in riptide
 - probably other changes that I don't remember
**1.2.0:**
 - Made hands appear when holding map
 - Changed bed model to have wooden sides, wooden foot, and wooden head
 - Updated shield animation to new 1.18 one
 - Made shield raise less, while still being animated
 - Fixed hand position when holding map
 - Changed the player render controller for map
 - Changed the player animation controller for map
 - Changed crossbow charging animation to appear higher up on screen
 - More changes & bugfixes... probably...
**2.0:**
 - Deleted all UI code, seeing as it was redundant
 - Implemented 3D boats from 3D items(by Yahirx_Rps_MC)
 - Made 3D flower pots and cauldrons; they are now data-driven
 - Changed the hit animation(many times)
 - Made the second arm appear when riding... bc why not?
 - Changed the crossbow position
 - Gave the third person bow animation a nice transition
 - Made the third person trident animation nicer
 - Made the third person crossbow animation closer to Java edition
 - Gave the third person crossbow animation a nice transition
 - Made the third person swimming animation based on speed
 - Fixed bugs with the third person swimming animation
 - Changed the positions of data-driven items when in riptide
 - Many other things that I probably forgot
 **2.1:**
 - Uploaded to github
**2.2:**
 - Fixed bow animation AGAIN
 - Fixed empty hand animation AGAIN
 - Fixed trident animation AGAIN
 - Removed 3D boats
 - Updated hit animation to more closely follow ambient's hit animation from Java 1.7 animations
 - Moved the left-handed subpack to its own seperate pack, that can be put on top of this
 - Removed the small shield model
 - The shield is now normal size, but is lower in first person
 - The 3rd person shield animation has transitions in and out now
 - Updated spyglass positioning
 - The left hand no longer appears when riding
 - Changed the first person crossbow charging animation
 - Added/improved transitions into the first person crossbow, trident, bow, and shield animations
 - Implemented running animation from Java 1.7 animations by ambient
 - Fixed the hand positioning while holding a map
 - Fixed the enchantment glint for more items
 - Made the 3rd person holding animation more similar to Java edition
 - Made certain items no longer float over the player's hand
 - Conduits are now data-driven, so don't appear way off the right of the screen