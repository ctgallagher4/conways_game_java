# Conway's Game of Life in the Terminal with Java
Conway's game of life is the first thing I do when learning a new language. To install, simply clone the repository, cd into it, and run this:
```
$ javac ConwaysGameOfLife.java
$ java ConwaysGameOfLife
```
Make sure your terminal is stretched to full screen. If it does not look correct, it is probably not and you will need to edit line 104:
```
Frame frame = new Frame(35, 19, .5f, 1000);
```
35 is the current width in terms of number of cells and 19 in the current height in terms of the number of cells. Your monitor and or fontsize may differ.
