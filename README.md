# Animation-library-final
Animation Library Final Project


Hello and welcome to my animation library.
The library features 17 animations and many of those animatons cover states such as :hover, :focus and :active.
To use the animations you need to add a "sassanimation" class to an element along with the name of the animation, duration and repeat count.
e.g: <p class="sassanimation tilt duration-3 repeat-infinite"></p>
The animations featured are:
1. 360 degrees spin (fullSpin)
2. 180 degrees spin (halfSpin)
3. 90 degrees  spin (thirdSpin)
4. Fade in animation (fadeIn)
5. Fade out animation (fadeOut)
6. Slight slide from left to right (miniLeft)
7. Slight slide from right to left (miniRight)
8. Slide left to right from out of left side of the screen (outOfScreenLeft)
9. Slide right to left from out of right side of the screen (outOfScreenRight)
10. Slide from right to the left side outside the screen (leftOutOfScreen)
11. Slide from left to right side outside the screen (rightOutOfScreen)
12. Slight slide down (down)
13. Slight slide up (up)
14. Sliding up and down (upDown)
15. Sliding left and right (leftRight)
16. Blast in animation (blastIn)
17. Tilting animation (tilt)
18. Jello animation (jello)
19. Hinge animation (hinge)
20. Flash animation (flash)
21. Swing animation (swing)

There are 6 different durations:
1. 1 second duration (duration-1)
2. 2 seconds duration (duration-2)
3. 3 seconds duration (duration-3)
4. 4 seconds duration (duration-4)
5. 5 seconds duration (duration-5)
6. 6 seconds duration (duration-6)

There are 5 different animation repetitions:
1. Repeat one time (repeat-1)
2. Repeat animation twice (repeat-2)
3. Repeat animation three times (repeat-3)
4. Repeat animation endlessly (repeat-infinite)
5. Leave the animation at its endpoint (forwards)
6. Reverese the animation after it reaches it's endpoint (alternate)

To change the animation's properties, or to add an animation, head to the keyframes.scss and you can change whatever you like.
To change or add durations, head to duration.scss
To change or add repetitions, head to repetition.scss

After adding an animation to the keyframes.scss you also need to add it in the classes.scss 
create a keyframes: @keyframes animationName {
from {} 
to {}
}
then in classes:
.sassanimate {
&.animationName {
animation-name: animationName;
}
}
}
