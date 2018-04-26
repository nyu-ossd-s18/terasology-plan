## April 5, 2018 
* We downloaded the code base
* We built the code with gradlew build
* We began to triage issues 
* We looked at bugs for beginners
* Some of us set up the code with IntelliJ using gradlew idea
* We looked at the code in IntelliJ
* We discussed the project change with the professor and took necessary steps to changing projects (renaming things, making repos in our project, creating milestones, etc.)
* We found issues we could work on as a group

## April 7, 2018 (Informal meeting to make progress on project)
* We played the game to have a better understanding of the controls
* We triaged issues 
* We recreated [Issue 3280](https://github.com/MovingBlocks/Terasology/issues/3280)
* We reached out on the Terasology Discord channel/IRC to ask whether the game had a feature where the player can see themselves in 3rd person
* We discussed ways to solve the bug, left a comment asking for more guidance
* We updated milestones
* We are still having issues trying to run the program on Ubuntu

## April 10, 2018 
* Ryan had issues trying to install the program onto the computer, so he messaged the Discord chat
* Ashley messaged the Discord for clarification and more information on an issue, looked at closed issues for more information
* Dora looked for more potential issues that could be worked on as a team as well as smaller issues; also had to reclone fork and set up properly with IntelliJ (cloned from the Terasology project the first time, then downloaded properly but accidentally opened before running ./gradlew idea); 
* the three of us noticed the create game menu for both singleplayer and multiplayer got cut off, Dora looked through the UI files and made the menu scrollable but later Suyasha told us that people were already working on that issue. Dora is still looking for ways to improve upon their solution

* Suyasha and Ola were not in class but looked for more potential issues that can be done

## April 11, 2018
* Suyasha added a snow block and Dora added a new texture for the snow block but that might've been the incorrect interpretation of what they were asking for
* Suyasha and Ryan did some multiplayer testing
* Dora working on making the player light up when a torch is held, tried testing with Ashley but couldn't quite get it to work, more research required
* Suyasha found a new issue regarding snow that involves giving players random damage as they walk on the snow.

## April 14, 2018 (Informal meeting to make progress on project)
* We found out what they were actually asking for when they wanted a snow slab
* Dora and Suyasha are looking into adding snow into the existing WeatherModule module
* Ryan is creating 1/2 and 1/4 snow slab textures 
* Ashley is working on damaging players as they walk on snow
* Ola is working on implementing snow slabs piling up into bigger snow blocks

## April 17, 2018
* Dora was looking at [broadcasting events](https://metaterasology.github.io/docs/developing/networkMultiplayer/networkEvents.html#broadcastevent) in her continued quest for solving the [torch issue](https://github.com/MovingBlocks/Terasology/issues/3280)
* Suyasha, Ashley, Ryan, and Ola continued to work on the snow blocks, Suyasha had previously noticed that when placed, the snow texture disappears on one side
* Ashley found out that she could not work on the initial issue of damaging players as they walk on snow because they got rid of systems in the current code that would make it possible
* Suyasha and Ashley found ingots which seemingly have similar logic to what is needed for the snow slab, Suyasha, Ashley, Ryan, Ola are looking through the ingot logic and structure to see if it could be implemented in a way that works for snow
* Dora and Ryan worked on reorganizing our repo since we had been committing to our fork instead of developing on separate branches
* Dora and Suyasha noticed the texture for the axe icon was backwards, Dora found the texture and created a PR

## April 18, 2018
* We continued to look at the issues we are working on
* We messaged the discord chat for help and information
* Found command for Ryan's game to run on his laptop: `LIBGL_ALWAYS_SOFTWARE=1 ./gradlew game`

## April 25, 2018
* Ola added content to the presentation and looked for another small fix to contribute.
* Suyasha continued working on the snow issue and snowshoes.
* Ryan asked for help on Discord about stacking snow.
* Ashley and Ryan worked on getting snow to stack.
* Dora looked into a UI fix.
