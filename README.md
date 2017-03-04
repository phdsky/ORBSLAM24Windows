# ORBSLAM24Windows
ORBSLAM2 Project 4(for) Windows Platform

Easy built orbslam2 by visual studio on windows of both debug and release mode

## Thanks
- Original ORBSLAM2 project: [ORB_SLAM2](https://github.com/raulmur/ORB_SLAM2)
- Eigen and Pangolin in Thirdparty are extracted from [Phylliida/orbslam-windows/Thirdparty](https://github.com/Phylliida/orbslam-windows/tree/master/Thirdparty)

## Prerequisite
1. OpenCV
 - Version is not required, but not too old. In this tutorial is 2.4.13.
 - Add `YOUR_OWN_PATH\opencv\build;` `YOUR_OWN_PATH\opencv\build\x64\vc12\bin;` to your environment variable "PATH", you can also add `YOUR_OWN_PATH\opencv\build\x86\vc12\bin;` if you want to bulid a x86 type application.
2. Cmake
 - Version should at least be 2.8.
3. Visual Studio
 - In this tutorial is VS2013(Corresponding to opencv's vc12). 

So, we'll build a visual studio 2013 project of ORB_SLAM2 using cmake and then make a x64 app. 
  
## Steps
First, we'll compile the projects in **Thirdparty** folder.
### DBoW2

### eigen

### g2o

### Pangolin
