# The editor closes when I change levels and I have an AudioCapture component on an actor.

## In unreal engine 5.1.0
-Create 2 levels.
-In the level blueprint place a delay to switch between the two levels every 3 seconds
-Create an actor pawn with a component of type "AudioCapture " and that is auto activated, you can also put an event on audioenvelopment change to see the current value of the audio.
-Place that pawn actor on the stage and make it autoposses player 0 to make it the main character of the game.
-de play and you will see that when you change the level the editor is checked.
-The strange thing is that it doesn't crash, it just crashes.

## You can try this in unreal engine 4.27 and export to android, you will see that when you change the level in android the same problem happens, the application closes suddenly.


After adding an AudioCapture component to a main actor and changing the level, the editor closes in unreal engine 5.1.0, in android the same thing happens in 4.27

Use the microphone in android to use it as input input.