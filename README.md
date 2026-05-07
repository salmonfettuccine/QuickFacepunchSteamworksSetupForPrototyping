# QuickFacepunchSteamworksSetupForPrototyping

CREDITS GO TO @pixelfizz1718 https://www.youtube.com/@pixelfizz1718 FOR PROVIDING THE TUTORIAL. PART 1 of the Tutorial: https://www.youtube.com/watch?v=kBgnIJUfQak&t=723s PART 2 of the Tutorial: https://www.youtube.com/watch?v=0QPIhCFWkAM&t=819s. Honourable mention: MrRobinOfficial https://www.youtube.com/watch?v=9CYsQ2Rsr2c.

Now, let me be **clear**. This is just to be able to connect with friends/playtesters through steam and play your multiplayer game for **prototyping** **purposes**! Yes, when you build and upload your Unity game using SteamPipe, Steam and Steam overlay will work (obviously you need to configure the launch settings in the steamworks page in order for your game to launch correctly when you press PLAY on Steam). How do you join/invite? Well, you must press SHIFT+TAB and right click on the friend you WANT to invite with access to your GAME, then press "Invite to Game". It's necessary to check out pixelfizz1718 tutorials, and for good measure, MrRobinOfficial's, if you want to expand and understand how the scripts inside work (also check Steam's Steamworks documentation).

**IMPORTANT:** I have NOT tested the scripts with Netcode for Gameobjects version 2.0-2.11.

**How to Implement:** Make sure you have installed Netcode for Gameobjects 1.15.1. Using the package manager -> Add package from git URL: https://github.com/Unity-Technologies/multiplayer-community-contributions.git#0eda04fc2146a4f907a61de6403315bce705279e This adds the option to use "FacepunchTransport" inside NetworkManager.


There is no license, do whatever you want with this.
