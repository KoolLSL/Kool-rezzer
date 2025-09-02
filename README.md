THE 3 KOOL REZZERS: MINI, PACK, AUTO
 
This new kind of rezzers does not need any script inside each object. It works even with your NO MOD objects ! Setting up your rezzer is simpler and faster than before.

Rezzing is safer too: it knows about each rezzed object to avoid duplicates or off sim/parcel. Objects are safe too: nothing overwrites description, script, data, particle or floating text. 

Note: Only rezzers coded after September 2024 can use such new SL functionalities. All previous rezzers, any brand, required a script to drop in each object and scripted copies.
COMMON TO THE 3 REZZERS

• ZERO SCRIPTS in objects. You finally can rez NO MOD objects !
• An easy way to store objects on the fly and checklist all is good.
• Can store +700 objects positions, anywhere in same sim.
• Optional rez status on floating text or by prim color.
• You can use your own prim/mesh as rezzer.
• LI counter to avoid “parcel full”.
• Off sim/parcel detection.
• Setup menu is for owner only.
• Fast and nice rez: objects are rezzed directly at their final positions, no weird moves and rotations.
• As objects don’t need to be scripted, objects won’t follow immediately when rezzer is moved (tracking), but they will be at correct position at next rez. However, with PACK, we still provide an optional track script if you really think it is worth the extra setup work. PACK provides a temporary Footprint prim as a better alternative.
Kool Rezzer MINI

• A simple standalone rezzer to rez BY MENU individual objects (+700) or groups (26 mini-scenes maxi). Use it to save prims or alternate decors in your home, skybox, rentals, club, RP sim, photo studio, etc.. 
• Configure user menu to show:
- All: single button to rez/derez all objects at once, no grouping.
- Any: one button per object/group, rez/derez any simultaneously.
- One: one button per object/group, rez one exclusively, previous one will derez first.
• Local positions.
• Sim/parcel limits detection to avoid uncomplete rez or parcel full.
• User menu access: owner, group, friends (while owner on sim), everyone.
• Copy / No trans / scripts No mod.
HOW TO STORE OBJECTS

1. Place your objects on sim in final positions.
2. Drop same objects into rezzer from Inventory.
3. Get setup menu (drag mouse off rezzer), click [Objects / Store] to start recording.
4. Go in Edit mode and select object(s) to store: rezzer will detect your selection.
5. Once add/update is confirmed in chat, delete selected objects (if they were not rezzed by this rezzer), and select next ones.
6. Click Stop to end recording.
7. To check, click the info links on menu to list stored objects.


• Each different object must have a unique name. However, a same object can be stored at multiple positions, in that case drop it only once inside rezzer. Ex: chairs around a table, trees, street lights… That’s why you may see, on purpose, more “stored positions” than objects in content.

• An object can of course be a large linkset made of multiple prims. If it has doors or moving parts, be sure they are closed or at initial positions before taking copy into inventory. They should preferably be linked to the build root. If there are scripts with long loading (sit script), wait they loaded 100% before taking copy. 

• During Store, you can select one object at a time and wait confirmation, but you can also multi-select all objects together, even hidden ones. It is not a problem if you re-select previous objects, or objects which are not in rezzer, or even objects of other owners: the rezzer considers only objects in content and ignores duplicates. But be cautious when deleting. If objects are far (about 100 m), move closer, the setup ball will follow you.

• For MINI and PACK, you can set one of the 26 groups available while storing. Groups can be renamed (name shown on menu button). Objects of same group rez/derez together. By default, objects are stored with no group (object name on menu button). You can change the group anytime or reverse to no group by re-storing selected objects.

• The rezzer can derez only objects it has rezzed itself. That’s why you need to delete yourself new objects stored for the first time. Click the info links on menu to list these “new” objects. The chat list has also clickable links to show each object position (particle effect). Be within 20 m of the rezzer when clicking links.

• You can store in cumulative sessions. Ex: you can store each house of a village one by one, without the whole village being rezzed at once. But DO NOT MOVE THE REZZER between partial store sessions. If you need to move the rezzer: rez all objects then re-store all positions again, so they are recorded from the same reference.

• In theory, you could even use “No copy” objects, but such object will rez only once, moving out of the rezzer, and won’t be derezzed. Also, to store it, you would need 2 copies (one in rezzer, one on sim). This is very specific. However, for PACK, it can be used to store objects copy for you but no copy for next owner: after transfer the end-user can rez them only once.
UPDATING REZZED OBJECTS

• If you modify a rezzed object (texture, size…), use your viewer menu [Build/Object/Save back to object content] which replaces the object inside rezzer by the one rezzed inworld. Best is to dock the menu [Object] meanwhile (click top bar). Alternatively, you can delete the old object in rezzer Content, take a new copy into Inventory and drop it inside. No need to re-do [Store] if name, position, rotation and LI are identical.

• If you changed only the position of a rezzed object, do [Store] again. No need to drop a new copy inside the rezzer if object is the same. No need to delete it yourself, the rezzer will derez it later.

• If you rename an object already stored, consider it as a new object to store. Use the menu [Unstore / Clean] to detect obsolete positions (object name previously stored but no more inside rezzer). Also, prefer short names for memory efficiency.

• To suppress an object, delete it in rezzer Content, and do [Objects / Unstore / Clean] to remove obsolete positions.
IMPORTANT NOTES

• NEVER DELETE OR TAKE A REZZER WHILE ITS OBJECTS ARE REZZED ! Objects would become “orphans”. Even if you restore the rezzer, objects cannot be derezzed again. Of course, if you just wanted to rez objects once and never need to derez them, you can delete the rezzer.

• NEVER LINK A REZZER AS A CHILD PRIM ! If it is unlinked later, it will lose all stored positions (because of the way LinkSetData works). However, you can link child prims to the rezzer as long the rezzer remains the root, but it’s risky. Take copy before trying.

• OBJECTS ARE DEFINITIVELY LOST WHEN DEREZZED ! They don’t go to the bin, they are “killed” on sim. With the AUTO rezzer, when editing a rezzed build, set Rez mode = OFF to be sure it won’t derez, for instance, if you leave sensor range (by crashing) or by timer.  Automatic derez is disabled during Setup menu, but setting OFF is safer if you do complex edits during long time or works on multiple rezzers at once.

• When you click the info links on menu or chat, be within 20 m of the rezzer for it “hears” you.

• The rezzer keeps track of each object it has rezzed. It knows what needs to be derezzed or rezzed without creating duplicates. Example: if you accidentally delete half of a rezzed house, at next rez it will rez only the missing half.

• It is not a problem to reset the rezzer script (but you never need to).

• If you accidently delete the SETUP object from the rezzer, no worry, just find one from an original rezzer and drop it inside.

• Converting your v2 rezzers to v3 must be done with the special script. Please read the CONVERTER notecard.

• Like for all rezzers, these SL rules apply for rezzing:
“Silently fails if you don't have offline building rights on the land. To have the right, rezzer needs to either:
Be on land you own yourself.
Be on land where anyone is allowed to build, e.g. a sandbox.
Be set to the same group that owns the land and the land have the parcel flag 'allow group to build' set.
The group role "Always allow 'Create Objects'" will only work to override this when you are online and in the region...”

• Please contact Kool Mekanic for any questions or suggestions ;)
Join freely "Kool door Users" group for help.

• More Kool items at main shop or on Marketplace: https://marketplace.secondlife.com/stores/47415
