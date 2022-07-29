# This is an hypothetical assignment for a processing class.

This directory contains a directory with skeleton code, and a directory with example submission. Not that these submission contain various mistakes and errors. Note also that not all requirements are (easily) testable. They are illustative for what requirement may say, regardless of whether they can be turned in to an easy test.


## The assignment

You are given some skeleton code. It contains the beginning of a processing program to animate a march of some some penguins. You will find the main tab, plus classes for the Landscape, the Penguin and the Beak. The Landscape is finished, the Penguin partly finished, and the Beak mostly unfinished. 

The task is to finish the animation given the folowing requirements

### Requirements
* Main Tab
  * Create a colony of 7 Penguins. The intial x-position for each penguin should be random, the y-position at groundLevel of the southPole. The intial velocity should be chosen randomly between 0.5 and 1.5).
  * Use the Landscape for the SouthPole. The ground is set at 2/3th of the screen.
  * Inbetween the hills and the ground, display the penguins, and have them walk over the south pole with the colony.
  * If you press the mouse, it should select one penguin.
  * If you release the mouse, it should deselct all penguins.
  * If you drag the mouse, it should move the penguins. (Only the selected penguins. To move a penguin only if it is selected, is however part of the penguin implementation and should not be implemented here)
* Beak Class
  * The constructor should set the initial position, and size of the beak.
  * The display method should display the beak. Use part of the Penguin display method that draws the beak. You will have to modify it.
  * The move method should move the beak when the squeakConter is strictly positive. This means that the beak should open up and then close again. The upper half up to 45 degrees above, and the lower half 45 degrees 45 degrees below the 0 degree line. You can use the attribute angle, angularSpeed to achieve the effect. Each time the beak is closed decrement the squeakCounter.
  * The squeak method sets the squeakCounter to 3.
* Lanscape Class
  * Don't touch the Lanscape class.
* Penguin



