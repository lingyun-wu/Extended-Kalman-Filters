# Extended Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

[//]: # (Image References)
[image1]: ./output/image1.png
[image2]: ./output/image2.png


## Project Basics

In this project, an Extended Kalman Filter(EFK) with C++ is implemented to estimate the state of a moving object of interest with noisy lidar and radar measurements. The system fuses both of these two measuarements to predict the position of the moving object. All of the source codes of EFK can be found [here](https://github.com/lingyun-wu/CarND-Term2-P1/tree/master/src).

The liadar and radar measurments are generated by a simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases).

This repository includes two files, `install-ubuntu.sh` and `install-mac.sh`, that can be used to set up and install [uWebSocketIO](https://github.com/uWebSockets/uWebSockets) for either Linux or Mac systems. 


---

## Dependencies

* cmake >= 3.5
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

---
## Basic Build Instructions


1. Clone this repo.
2. Install uWebSocketIO with `install-ubuntu.sh` or `install-mac.sh`
3. Make a build directory: `mkdir build && cd build`
4. Compile: `cmake .. && make` 
   * On windows, you may need to run: `cmake .. -G "Unix Makefiles" && make`
5. Run it: `./ExtendedKF `


---
## Results

The simulator provides two data sets.

1. Here is the tracking result for data-set 1.


| Variable |     RMSE     |
|:--------:|:------------:| 
| px       |     0.0973   |
| py       |     0.0855   |
| vx       |     0.4513   |
| vy       |     0.4399   |


![alt text][image2]




2. Here is the tracking result for data-set 2.

| Variable |     RMSE     |
|:--------:|:------------:|
| px       |     0.0726   |
| py       |     0.0965   |
| vx       |     0.4216   |
| vy       |     0.4932   |

![alt text][image1]





