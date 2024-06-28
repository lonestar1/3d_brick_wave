# Project Title

A simple wave effect used as the foundation for the Cobble Stone street effect in Heineken Past Experience TVC. This project can be found on my website.

## Getting Started

Open the Maya scene and rewind to frame 1. This will reset all bricks to their first position. Hit play and ensure you have "play every frame" set in your Maya preferences.

## Running the tests

The bricks are driven by an expression which can be edited in the expression editor. There you can change the name of the objects you want the scrtipt to search for and set some variables to alter the speed at which the flipping occurs. 

Animate the clusters in the guide group to drive the nurbs surface. Varying the height will also change the height to which the bricks animate. 

In the expression editor you can disable the brick animation whilst working on the nurbs surface animation by turning the $evaluate value to 0 in the expression editor. This makes it easier to work with. 

On the "guide" nurbs surface there are some animation curves that drive the perfomance of the individual bricks. ie "Coble Ty" will control how the bricks animate up and down. The curve range read by the expression is between frames 0 and 1. Any values outside of this are ignored. 

Other variables in the expression can be tweaked such as "$turnover_frames" which will set how many frames the entire flip animation will take place over.

NB. Parallel evaluation mode (under animation settings) will not update the viewport correctly in some versions of Maya. Switch to DG mode to view the performance.

## Built With

Autodesk Maya

## Authors

* **Andreas Wanda** - *Initial work* - [lonestar1](https://github.com/lonestar1)
[www.andreaswanda.com](http://www.andreaswanda.com)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Thanks to Fuel International Post Production (Sadly no longer around)
