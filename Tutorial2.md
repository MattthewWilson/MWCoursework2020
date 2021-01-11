## Tutorial 2 - Options Menu

This tutorial continues on from the previous one and will assume you have read it, but can still be used as its own.

Within the canvas game object, add a new empty game object. Call this object "optionsMenu". Create a new C# script, call it "optionsMenuScript" and add it to the optionsMenu object. Within this script we will add the required functionality for a settings menu.

Before adding anything to the script, first create a slider, which can be found under UI, and add it under the optionsMenu. This will be used to control the audio volume. In order to make it do that, open optionsMenuScript. void Update will not be used for this script and can be safely deleted to keep things tidy.

To control the audio we will first need to be able to reference the volume from the audio manager. To do this click on "window" at the top of the screen , create a new method and call it "SetVolume (float volume)".
