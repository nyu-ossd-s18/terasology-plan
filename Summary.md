## List of attempted/considered issues 
<include brief comment stating if you decided to work on it or not and how successful the work was>
<include link in issue number>


Issue number | Brief description | Worked on?
--- | --- | --- 
[Issue 3307](https://github.com/MovingBlocks/Terasology/issues/3307) | Add command for permanent daytime for dev purposes | Claimed but got sniped
[Issue 3267](https://github.com/MovingBlocks/Terasology/issues/3267) | Players could jump on the surface of the water | Got sniped
[Issue 2585](https://github.com/MovingBlocks/Terasology/issues/2585) | Some menu screens would get cut off if screen wasn't in full screen mode | Ryan, Ashley, Dora noticed this issue and Dora created a small fix by making the menu scroll and wrote up an issue + solution but then Suyasha told us they knew about this issue already and showed us this previously created issue, where they discussed that making the menu scroll didn't work well with drop downs and someone was in process of making a drop up. Dora took another look at possibly getting the drop down height and adding it to the length of the menu so the scrollable area would be sized correctly but she and Ola determined this was out of scope
[Issue 3280](https://github.com/MovingBlocks/Terasology/issues/3280) | If you held a torch in multiplayer other people couldn't see the light | Worked on for a long time: Dora read [some](https://metaterasology.github.io/docs/developing/networkMultiplayer/networkEvents.html) [documentation](https://metaterasology.github.io/docs/developing/entitySystem/events.html?highlight=receiveevent), made commits (see below), tested with Ashley and Ryan, but ultimately issue got sniped
[Issue 2943](https://github.com/MovingBlocks/Terasology/issues/2943) | Torch still lights up underwater | Seemed out of scope
N/A | Suyasha and Dora noticed the axe texture was backwards | Successfully made a PR
N/A| Ola noticed that the read me didn't include a link to their Discord or a link to IntelliJ download for those who might be interested| PR is open

## List of pull requests with current status and who worked on it
<!-- Status options: accepted, rejected, still waiting, making changes, etc-->
<include link in PR number>


PR number | Status | Who worked on it? | Brief description 
--- | --- | --- | ---
[PR 3330](https://github.com/MovingBlocks/Terasology/pull/3330) | Accepted | Dora | PR to fix the backwards axe texture as noted [here](https://github.com/MovingBlocks/Terasology/pull/2876)
[PR 3339](https://github.com/MovingBlocks/Terasology/pull/3339#issuecomment-384012084)| Open | Ola |add links to read me as mentioned above

## For each group member individually: 
List of commits to the fork repository in the class organization

**Dora:** 
- dev-axe: [Commit to fix the axe texture](https://github.com/nyu-ossd-s18/Terasology/commit/3f1a7362c11be845093400d43acf979c663f896d)
- dev-torch: (some commits look like they are in dev-snow but that was from before our fork was separated into branches)
  - [First attempt at giving player LightComponent if they are holding a torch](https://github.com/nyu-ossd-s18/Terasology/commit/619842f2501b9932dd72398996c6274aec775bb9)
  - [First attempt cont., to take off LightComponent on player if they aren't holding a torch](https://github.com/nyu-ossd-s18/Terasology/commit/1f55a33549bcd7c361debfe957e1e3d9cf1f0605)
  - [Second attempt at fixing torch issue](https://github.com/nyu-ossd-s18/Terasology/commit/622dc57ff1b1ee87e9570ebe08c759338cd6127b)
  - [Second attempt cont.](https://github.com/nyu-ossd-s18/Terasology/commit/f11232811ab65de761938a3c89f60f1c486d67a4)
  - (I was about to commit attempt three until issue got sniped)
- dev-snow:
  - [Suyasha asked me to make a texture for her](https://github.com/nyu-ossd-s18/Terasology/commit/d93049deaaa80899c4e92f0820b0a8808cd34ecc)
  - (I made commits to dev-snow that should've been for dev-torch, see above)
  - (I made other commits to dev-snow before we separated our fork into branches, so I made a few commits to clean up previous commits made that didn't belong in this branch) 

**Ola:**
- TBA

**Ryan:**
- TBA

**Ashley:**
- dev-snow: 
The first 2 commits were my initial attempts at adding damage on the snow block. I continued working on the code for a bit, and then I eventually asked for clarification on a question that I had about the feature in the discord channel. However I was told that the system was gone due to technical limitations so it was not feasible for me to implement damage on snow blocks, so I scrapped the other changes made to the code.  
  1. [First commit on adding entity to prefab](https://github.com/nyu-ossd-s18/Terasology/commit/1e727ba8959a49653c2b37a98aaded1a20395036) 
  2. [Added damage component onto snow block](https://github.com/nyu-ossd-s18/Terasology/commit/837519fe52aa71184e9e31f2108a32393e4a185d)  
Began working on another issue starting here 
  3. [Setup of component classes and connecting it to snowslab block](https://github.com/nyu-ossd-s18/Terasology/commit/db27a5d8a65c8cbd879c3384568c1ca25ba642de) 
  4. [Added some initial logic to stack system](https://github.com/nyu-ossd-s18/Terasology/commit/75c6bbef859188bc9b29fd1e49a7f4f6e1ef2733)
  5. [Moved files not a new folder](https://github.com/nyu-ossd-s18/Terasology/commit/33319f0c8cb074b6b6b4abbab9c8d2eac350c630) 
  6. [Added missing import and fixed variable name](https://github.com/nyu-ossd-s18/Terasology/commit/5ecee086d6e284947f7d62b10517455f4fb35ced)
  

**Suyasha:**
- TBA
