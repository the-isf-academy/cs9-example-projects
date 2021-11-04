# Unit 0 Project: Animation

My project draws a flower-like pattern made of geometric "petals" that have a 3-dimensional element.
There are 3 concentric circles that make up the pattern, and these slowly spin as the animation moves.

## Intial Contents
This is the starter code for [Project 0: Animation](http://cs.fablearn.org/courses/cs9/unit00/project).
Here's what is included:

- `README.md` You're looking at it, or at least the formatted version. (Click "raw" to see the unformatted version.) Every project has a README explaining what it is.
- `project.py` When this is run, it should draw your project. (If your project is well-organized, there might not be much code in `project.py`. Instead, it might import functions from other modules.)
- `settings.py` This is where you will store your settings for your animation. Feel free to add more settings to further parameterize your project.

## Modules
I wrote the `helpers` module, and it helps create different parts the animation.
The draw_kite() function creates the smallest unit of the drawing.
The draw_cluster() function draws several "kites" so that it creates one petal of the drawing
The draw_circle() function draws many of the clusters, radiating out from one point. How many it draws will depend on the length parameter.

## Settings
SLEEPTIME affects the time in between each frame. The higher the sleeptime, the slower the animation will move.
NUMFRAMES is the number of frames in the animation. The higher the sleeptime, the longer the flower will keep spin.
NUMREPEATS is the number of times the animation repeats
SCREENWIDTH is the width of the screen
SCREENHEIGHT is the height of the screen
FILLCOLOR is the color of the clusters. If it's set to "random" the color will be random.
OUTLINECOLOR is the color of the outline of the clusters. If it's set to "random" the color will be random.

## How to use
To run the animation, type `python3 project.py` into the terminal
