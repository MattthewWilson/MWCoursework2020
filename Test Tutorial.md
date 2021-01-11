Tutorial for making an object move on a set path using animation.

Begin by creating the object you want to make move. In this example I will be using a basic box.

At top of unity there is a button labled "Window" Select this to open a drop down menu, and then select "Animation" And then "Animation" Again. This will open the animation tab.

In the animation tab click create and then name the animation file whatever you like, then save.

The animation window will now show a timeline.

Press on the record button, which has a red circle icon, then move your object to its starting position. This will save a new keyframe for that position.

Next select a later point in the timeline and then move the object to the location you want it to move to. This will save another keyframe in this position. If you now press play the object will move from the position of the first keyframe to the position of the second over the period of time between them in the timeline.

To make the animation loop, select the first keyframe and press Ctrl+C then select an even later point in the timeline and press Ctrl+V. This copies the first keyframe to a point after the second, which will make the object move back to the starting point.

Finally, press the record button again to stop recording keyframes.

Pressing play will now cause the object to move back and forth along the set path. By using more keyframes, more complex animations could be set up.
