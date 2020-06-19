## Fill Solver - Solver for AppStore game *Fill One-Line Puzzle Game*
### Special Thanks to Kimberly Kao ###
Thanks to Kimberly Kao (Github: kimberly-kao) for her help in VASTLY improving the UI of my android app. 
Her contributions are as follows
   - Create solution animation (fills in solution path one by one)
   - Created Drawables to set as button backgrounds
   - Reorganized layout of application 

### App Description
This is an Android Application that solves game boards generated by the game *Fill One-Line Puzzle Game*. 

IDE: Android Studios 4.0

SDK: Android 9.0 (Pie) or API Level 28

AVD: Pixel 1080 x 1920 resolution; 420 dpi

### Algorithm Used
The program uses a Recursive Backtracking. 

### App Walk-though
Example Game Board         |  Using Program
:-------------------------:|:-------------------------:
<img src="https://github.com/samliu000/FillSolver/blob/master/ReadMeAssets/ExampleGameBoard.PNG" width=250><br>  |  <img src="https://github.com/samliu000/FillSolver/blob/master/ReadMeAssets/Demo.gif" width=250><br>

## How To Use The App
**Set A Starting Point**
1. Click the "Set Start" Button
2. Click the cell that represents the starting position on the grid
   - If no starting point is set, the program defaults to (0,0) as the starting point
  
**Remove Spaces From Grid**
1. Click on the cells in the grid to remove them
   - Clicking on a cell again will unremove it
   
**Start the Solver**
1. Once the starting cell has been selected and the necessary cells removed, click on the start button to start the program

**Resetting**
1. To reset, press the reset button
   - Starting Point will be removed
   - Removed Cells will be unremoved
   
## Output
Once the user presses the start button, the program will assign each cell in the grid a number representing the order in which the cells should be filled up. 

It will also highlight the solution path one cell at a time (every 100ms). If you blink and miss that animation, you can press the replay button (right above the "Start" button) to restart the animation.

**Example**

<img src="https://github.com/samliu000/FillSolver/blob/master/ReadMeAssets/answerExampleWithHighlight.png" width=250><br>
