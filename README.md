# XM8-Air-Strike.
Updated 10/7/2021
This update includes alot of fixes. 1st fix was to get the script to end completely when jet was shot down or left due to time being up. Removed the config file to get rid of 
global variables and use all local variables. 2nd fix was adding in a message displaying how long player has to wait in seconds to call new strike, the time displayed updates with new time each press of button. 3rd fix was to reset the cooldown to zero when player gets message about needing laser designator so they can actually use press it and use it when they equip the designator instead of waiting for cooldown since they did not actually get the jet yet. Added in code for jet to have unlimited ammo so player can blow up as many targets as they want in the time the jet is active for them. 4th fix was deleting the pilot if jet gets shot down so they do not stay on the server using up resources.

If you have any questions contact Crito at https://discord.gg/HMFVyAy

Updated 8/24/2021
Thanks to The Tall Man for the extra features he added and the server side code for the respect cost!

This will call in air strike for player and strike targets that player designates with laser.

This script will use button in XM8 for Exile players to call an Air Stike at their position.
They will click the button and XM8 will close automatically with a message saying that the air stike is inbound.
They are required to have a laser designator with batteries to laser targets for the jet to bomb.
If no laser is detected by the pilot the jet will just circle the area looking for lasers and will not attack without a laser target.
Once the time for air stike is up the player gets message that its returning to base and leaves toward bottom left of map for deletion.
2 things to note is players calling different strikes on different locations close to each other at same time will not work because both jets will
go to the closest laser they find to the jet position. Also they may get hung up on roaming AI due to, still trying to figure out the code to get them
to ignore other targets.
