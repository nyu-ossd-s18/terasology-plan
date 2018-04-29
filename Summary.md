## List of attempted/considered issues 
<include brief comment stating if you decided to work on it or not and how successful the work was>
<include link in issue number>


Issue number | Brief description | Worked on?
--- | --- | --- 
[Issue 3307](https://github.com/MovingBlocks/Terasology/issues/3307) | Add command for permanent daytime for dev purposes | Claimed but got sniped
[Issue 3267](https://github.com/MovingBlocks/Terasology/issues/3267) | Players could jump on the surface of the water | Got sniped
[Issue 2585](https://github.com/MovingBlocks/Terasology/issues/2585) [Issue 1627](https://github.com/MovingBlocks/Terasology/issues/1627) | Some menu screens would get cut off if screen wasn't in full screen mode | Ryan, Ashley, Dora noticed this issue and Dora created a small fix by making the menu scroll and wrote up an issue + solution but then Suyasha told us they knew about this issue already and showed us this previously created issue, where they discussed that making the menu scroll didn't work well with drop downs and someone was in process of making a drop up. Dora took another look at possibly getting the drop down height and adding it to the length of the menu so the scrollable area would be sized correctly but she and Ola determined this was out of scope
[Issue 3280](https://github.com/MovingBlocks/Terasology/issues/3280) | If you held a torch in multiplayer other people couldn't see the light | Worked on for a long time: Dora read [some](https://metaterasology.github.io/docs/developing/networkMultiplayer/networkEvents.html) [documentation](https://metaterasology.github.io/docs/developing/entitySystem/events.html?highlight=receiveevent), made commits (see below), tested with Ashley and Ryan, but ultimately issue got sniped
[Issue 2943](https://github.com/MovingBlocks/Terasology/issues/2943) | Torch still lights up underwater | Seemed out of scope
N/A | Suyasha and Dora noticed the axe texture was backwards | Successfully made a PR
N/A| Ola noticed that the read me didn't include a link to their Discord or a link to IntelliJ download for those who might be interested| PR was accepted
[Issue 2406](https://github.com/MovingBlocks/Terasology/issues/2406) | Snow stuffs | Main group issue involving the addition of snow slabs, its associated functionality, and snow shoes to the game.

## List of pull requests with current status and who worked on it
<!-- Status options: accepted, rejected, still waiting, making changes, etc-->
<include link in PR number>


PR number | Status | Who worked on it? | Brief description 
--- | --- | --- | ---
[PR 3330](https://github.com/MovingBlocks/Terasology/pull/3330) | Accepted | Dora | PR to fix the backwards axe texture as noted [here](https://github.com/MovingBlocks/Terasology/pull/2876)
[PR 3339](https://github.com/MovingBlocks/Terasology/pull/3339#issuecomment-384012084)| Accepted| Ola |add links to read me as mentioned above

## For each group member individually: 
List of commits to the fork repository in the class organization

**Dora:** 
- [dev-axe](https://github.com/nyu-ossd-s18/Terasology/commits/dev-axe): [Commit to fix the axe texture](https://github.com/nyu-ossd-s18/Terasology/commit/3f1a7362c11be845093400d43acf979c663f896d)
- [dev-torch](https://github.com/nyu-ossd-s18/Terasology/commits/dev-torch): (some commits look like they are in dev-snow but that was from before our fork was separated into branches)
  - [First attempt at giving player LightComponent if they are holding a torch](https://github.com/nyu-ossd-s18/Terasology/commit/619842f2501b9932dd72398996c6274aec775bb9)
  - [First attempt cont., to take off LightComponent on player if they aren't holding a torch](https://github.com/nyu-ossd-s18/Terasology/commit/1f55a33549bcd7c361debfe957e1e3d9cf1f0605)
  - [Second attempt at fixing torch issue](https://github.com/nyu-ossd-s18/Terasology/commit/622dc57ff1b1ee87e9570ebe08c759338cd6127b)
  - [Second attempt cont.](https://github.com/nyu-ossd-s18/Terasology/commit/f11232811ab65de761938a3c89f60f1c486d67a4)
  - (I was about to commit attempt three until issue got sniped)
- [dev-snow](https://github.com/nyu-ossd-s18/Terasology/commits/dev-snow):
  - [Suyasha asked me to make a texture for her](https://github.com/nyu-ossd-s18/Terasology/commit/d93049deaaa80899c4e92f0820b0a8808cd34ecc)
  - (I made commits to dev-snow that should've been for dev-torch, see above)
  - (I made other commits to dev-snow before we separated our fork into branches, so I made a few commits to clean up previous commits made that didn't belong in this branch) 
  - [Added snowshoe texture and added to item atlas](https://github.com/nyu-ossd-s18/Terasology/commit/7e39860f84716290192b96aea55c62c6773c6eac)
  - [Modified snowshoe texture, added to game by editing prefab](https://github.com/nyu-ossd-s18/Terasology/commit/006b5a94ad3567beeec8d3ac3fce4cd4fdedcc92)
- [dev-ui](https://github.com/nyu-ossd-s18/Terasology/commits/dev-ui)
  - (didn't commit yet but modified UI files to try fixing issue with dropdown menus)

**Ola:**
- dev-docs [edits for submitted pr](https://github.com/nyu-ossd-s18/Terasology/commit/8106634720bfdf5598be823dcd1fb1ee848660fc)

**Ryan:**
- dev-snow:
  - [Adding stuff from Structural Resources to create slabs](https://github.com/nyu-ossd-s18/Terasology/commit/374e9bb635bf60d757474434585bb73643a3da59)
  - [GIT MAN SAVES THE DAY](https://github.com/nyu-ossd-s18/Terasology/commit/d32be035babbe763d7d997df867c860f19f6ddac)
  - [Setting up to replicate ingots from Structural Resources](https://github.com/nyu-ossd-s18/Terasology/commit/4117d314918953de1a11e7ecaca88adf6d0249af)
  - [Adding stack shapes from Structural Resources](https://github.com/nyu-ossd-s18/Terasology/commit/b85028cec820810cd46ee4607e6538c2d0b9e87f)
  - [Added some prefabs and blocks to try to get ingots to work](https://github.com/nyu-ossd-s18/Terasology/commit/b6760491dd2a62c9789f21b375642d8c256a3893)
  - [GIT MAN TO THE RESCUE](https://github.com/nyu-ossd-s18/Terasology/commit/5f239cce59f9d1323556900aec39c49350ef5b76)
  - [Fixed a missing bracket in IngotComponent.java](https://github.com/nyu-ossd-s18/Terasology/commit/79f9e25296c4af988068d1c6f368a22dbb5b78de)

**Ashley:**
- dev-snow: 
The first 2 commits were my initial attempts at adding damage on the snow block. I continued working on the code for a bit, and then I eventually asked for clarification on a question that I had about the feature in the discord channel. However I was told that the system was gone due to technical limitations so it was not feasible for me to implement damage on snow blocks, so I scrapped the other changes made to the code.  
  - [First commit on adding entity to prefab](https://github.com/nyu-ossd-s18/Terasology/commit/1e727ba8959a49653c2b37a98aaded1a20395036) 
  - [Added damage component onto snow block](https://github.com/nyu-ossd-s18/Terasology/commit/837519fe52aa71184e9e31f2108a32393e4a185d)  
Began working on another issue starting here 
  - [Setup of component classes and connecting it to snowslab block](https://github.com/nyu-ossd-s18/Terasology/commit/db27a5d8a65c8cbd879c3384568c1ca25ba642de) 
  - [Added some initial logic to stack system](https://github.com/nyu-ossd-s18/Terasology/commit/75c6bbef859188bc9b29fd1e49a7f4f6e1ef2733)
  - [Moved files not a new folder](https://github.com/nyu-ossd-s18/Terasology/commit/33319f0c8cb074b6b6b4abbab9c8d2eac350c630) 
  - [Added missing import and fixed variable name](https://github.com/nyu-ossd-s18/Terasology/commit/5ecee086d6e284947f7d62b10517455f4fb35ced)]
  - [Fixed a broken link](https://github.com/Terasology/TutorialAssetSystem/wiki/Add-A-Dice/_history)
  

**Suyasha:**
- dev-snow:
  - [Add quarter snow slab](https://github.com/nyu-ossd-s18/Terasology/commit/f922805e1badefde9c84a76d524ffb6755a8020e)
  - [Add half snow slab](https://github.com/nyu-ossd-s18/Terasology/commit/6be3801c544ce64c76899f45fdbbfac5975d2b07)
  - [Add eight snow slab](https://github.com/nyu-ossd-s18/Terasology/commit/b59599893f260ed9017d4ca1df9471618644c143)
  - [Add texture to slab](https://github.com/nyu-ossd-s18/Terasology/commit/c3bc1e773ce86542fe0c48ed83a6f889cd9799c1)
  - [Make eight snow slab penetrable](https://github.com/nyu-ossd-s18/Terasology/commit/4aeacafdb42fde3cbbbcc0eb1f2c3b6f0895ce24)
  - [Fixed typo](https://github.com/Terasology/TutorialAssetSystem/wiki/Add-A-Dice)
