# EYEtrack 

## Using gazes and blinks to control computer actions

An attempt at gradient based gaze tracking (algorithm taken from Fabian Timm)

The program uses OpenCV and Haar Cascades to detect both blinking and gaze tracking.
The gaze tracking software is based off of that of eyeLike (https://github.com/trishume/eyeLike)


## Disclaimer

This code is in a very alpha state, and currently doesn't use gaze tracking to implement any
actions yet. The code between blinking and gaze tracking is not integrated, and the two versions remain in both Python and C++

## Building

### Gaze Tracking 
 
* Install CMake through your distribution
* Install the OpenCV libraries for C++

### Blinking
1. Install OpenCV Python library
 * pip install opencv
 * Install scientific analysis tools (not necessary, but speeds them up)
2. pip install numpy
	* pip install scipy
	* pip install matplotlib



##References

Timm and Barth. Accurate eye centre localisation by means of gradients. In Proceedings of the Int. Conference on Computer Theory and Applications (VISAPP), volume 1, pages 125-130, Algarve, Portugal, 2011. INSTICC.
