---
title: "Prisoners of Bubbleville: Design Brief"
date: 2024-08-23
---



# Prisoners of Bubbleville: Design Brief

- make a videogame all about parachuting into a city
## Story
- You are “Smiley,” a parachuting cat. The good people of Bubbleville are trapped in their houses by an evil wizard. You must find a way to defeat the wizard, by repeatedly parachuting into the city and sliding down chimneys to visit the citizens and get clues about how to stop the wizard.
## Mechanics
- As you parachute toward the city, you are trying to grab magic bubbles that rise up from the city and use their energy to shoot rays at evil vultures that try to pop the bubbles and rip your parachute. Simultaneously, you must navigate down to one of several target buildings in the city.
## Aesthetics
- A cartoony look and feel.
## Technology
- Multiple platform 3D console game using a third-party engine.
---
# Prisoners of Bubbleville: Risk List
- Risk #1: The bubble collecting/vulture shooting mechanic might not be as fun as we think.
- Risk #2: The game engine might not be able to handle drawing an entire city and all those bubbles and vultures at once.
- Risk #3: Our current thinking is that we need thirty different houses to make a full game—creating all the different interiors and animated characters might take more time than we have.
- Risk #4: We aren’t sure people will like our characters and story.
- Risk #5: There is a chance the publisher might insist we theme this game to a new summer movie about stunt parachuting.
---
# Prisoners of Bubbleville: Risk Mitigation
1. Game mechanics can often be abstracted and played in a simpler form. Have a programmer make a very abstract version of this gameplay mechanic, perhaps in2D, with simple geometric shapes instead of animated characters. You can probably have a working game in a week or two and start answering questions about whether it is fun right away. If it isn’t, you can make quick modifications to the simple prototype, until it is fun, and then begin work on the elaborate 3D version. You’ll be doing more loops sooner, wisely taking advantage of the Rule of the Loop. You might object to this approach, thinking that throwing out the 2D prototyping code, which the players will never see, is wasteful. In the long run, though, you would have saved time, because you will be coding the right game sooner and not endlessly coding and recoding the wrong game.
2. If you wait for all the final artwork to answer this question, you could put yourself in a horrible situation: if the game engine can’t handle it, you now have to ask the artists to redo their work so it is less strain on the game engine or ask the programmers to spend extra time trying to find tricks to render everything more efficiently (or most likely, both of these things). To mitigate the risk, build a quick prototype, right away, that does nothing but show the approximate number of equivalent items on screen, to see if the engine can handle it. This prototype has no gameplay; it is purely to test technical limits. If it can handle it, great! If it can’t, you can figure out a solution now, before any art has been generated. Again, this prototype will be a throwaway.
3. If you get halfway into development before you realize that you don’t have the resources to build all the artwork, you are doomed. Have an artist create one house and one animated character immediately to see how long it takes, and if it takes longer than you can afford, change your design immediately—maybe you could have fewer houses, or maybe you could reuse some the interiors and characters.
4. If you really are concerned about this, you cannot wait until the characters and story are in the game to find out. What kind of prototype do we build here? An art prototype—it might not even be on a computer—just a bulletin board. Have your artists draw some concept art or produce test renders of your characters and settings. Create some storyboards that show how the story progresses. Once you have these, start showing them to people (hopefully people in your target demographic) and gauge their reactions. Figure out what they like, don’t like, and why. Maybe they like the look of the main character but hate his attitude. Maybe the villain is exciting, but the story is boring. You can figure most of this out completely independent of the game. Each time you do this and make a change, you’ve completed another loop and gotten one step closer to making a good game.
5. This risk might sound absurd, but this kind of thing happens all the time. When it happens in the middle of a project, it can be horrible. And you can’t ignore this kind of thing—you must seriously consider every risk that might threaten your project. Will a prototype help in this case? Probably not. To mitigate this risk, you can lean on management to get a decision as fast as possible, or you could decide to make a game that could more easily be rethemed to the movie. You might even come up with a plan for making two different games—the key idea is that you consider the risk immediately and take action now to make sure it doesn’t endanger your game.
---