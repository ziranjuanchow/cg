[![Build Status](https://travis-ci.org/danielepanozzo/cg.svg?branch=master)](https://travis-ci.org/danielepanozzo/cg)
[![Build status](https://ci.appveyor.com/api/projects/status/3b1dti4xig8i3c4a?svg=true)](https://ci.appveyor.com/project/danielepanozzo/cg)

# Graduate Computer Graphics, CSCI-GA 2270-001 Fall 2017

### Course Instructor
*Daniele Panozzo*

60 5th Ave, 5th Floor

Phone: 212 998 3208

[panozzo@nyu.edu](mailto:panozzo@nyu.edu)

URL: [http://cs.nyu.edu/~panozzo/](http://cs.nyu.edu/~panozzo/)

Office Hours: Mondays, 5pm-6pm and by appointment, 60 5th Ave, 5th Floor, Room 504

### Assistant
*Zhongshi Jiang*

[jiangzs@nyu.edu](mailto:jiangzs@nyu.edu)

[http://cs.nyu.edu/~zhongshi/](http://cs.nyu.edu/~zhongshi/)

Office Hours: Tuesdays and Thursday, 2pm-3pm, 60 5th Ave, 5th Floor, Room 540.

### Lectures:
Mondays at 7:10pm - 9pm
60 Fifth Ave C10

## Course Description

This course provides an introduction to the field of Computer Graphics. We will cover the basic mathematical concepts, such as 2D and 3D transformations, study the interaction of light with geometry to derive  shading models, and implement rendering algorithms such as ray tracing and rasterization. We will investigate how these fundamental components are integrated in current graphics processors and study the corresponding programming APIs. This course will also include a brief introduction to C++.

Students will experiment with modern graphics programming and build small demos in C++ and OpenGL.

By the end of the course, the student must be able to:

* Explain and apply the fundamental mathematical concepts used in  image synthesis algorithms
* Implement a basic rendering system based on ray tracing
* Implement a basic rendering pipeline based on rasterization
* Develop simple graphics programs in C++ using OpenGL and GLSL

*Textbook*:
Fundamentals of Computer Graphics, 4th Edition
December 18, 2015 by A K Peters/CRC Press
Textbook - 734 Pages - 541 Color
ISBN 9781482229394

## Schedule and Course Notes:

The course schedule is tentative and *will* be adjusted along the way.

* 09/11: [01 - Introduction, Images  (Chapters 1, 2, 3)](http://cs.nyu.edu/~panozzo/cg17/Slides/01%20-%20Introduction,%20Images.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/01%20-%20Introduction,%20Images.key.zip)
* 09/18: [02 - Ray Tracing, C++ (Chapter 4, 10)](http://cs.nyu.edu/~panozzo/cg17/Slides/02%20-%20Ray%20Tracing,%20C++.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/02%20-%20Ray%20Tracing,%20C++.key.pdf)

[*Assignment 1: Ray tracing*](Assignment_1/requirements/Assignment-1_Ray_Tracing.pdf)

* 09/25: [03 - Basic Linear Algebra and 2D Transformations (Chapters 2, 5, 6)](http://cs.nyu.edu/~panozzo/cg17/Slides/03%20-%20Basic%20Linear%20Algebra%20and%202D%20Transformations.pdf) [ (keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/03%20-%20Basic%20Linear%20Algebra%20and%202D%20Transformations.key.zip)
* 10/02: [04 - Viewing Transformations and Rasterization (Chapter 7, 8)](http://cs.nyu.edu/~panozzo/cg17/Slides/04%20-%20Viewing%20Transformations,%20Rasterization.pdf) [ (keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/04%20-%20Viewing%20Transformations,%20Rasterization.key.zip)
* 10/16: [05 - The OpenGL Graphics Pipeline (Chapter 8, 17, http://open.gl)](http://cs.nyu.edu/~panozzo/cg17/Slides/05%20-%20The%20OpenGL%20Graphics%20Pipeline.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/05%20-%20The%20OpenGL%20Graphics%20Pipeline.key.zip)

[*Assignment 2: 2D Vector graphics editor*](Assignment_2/requirements/Assignment-2_2D_Editor.pdf)

* 10/23: [06 - The OpenGL Graphics Pipeline - Part 2 (Chapter 8, 17, http://open.gl)](http://cs.nyu.edu/~panozzo/cg17/Slides/06%20-%20The%20OpenGL%20Graphics%20Pipeline%20Part%202.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/06%20-%20The%20OpenGL%20Graphics%20Pipeline%20Part%202.key.zip)

* 10/30: [07 - Designing Interpolating Curves (Chapter 15)](http://cs.nyu.edu/~panozzo/cg17/Slides/07%20-%20Designing%20Interpolating%20Curves.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/07%20-%20Designing%20Interpolating%20Curves.key.zip)

* 11/06: [08 - Designing Approximating Curves (Chapter 15)](http://cs.nyu.edu/~panozzo/cg17/Slides/08%20-%20Designing%20Approximating%20Curves.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/08%20-%20Designing%20Approximating%20Curves.key.zip)

[*Assignment 3: 3D Mesh viewer*](Assignment_3/requirements/Assignment3_3D.pdf)


* 11/13: [09 - Designing Surfaces (Chapter 7)](http://cs.nyu.edu/~panozzo/cg17/Slides/09%20-%20Designing%20Surfaces.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/cg17/Slides/09%20-%20Designing%20Surfaces.key.zip)

*Assignment 4: Final Project Discussion*

* 11/20: [10 - Texture Mapping (Chapter 11)](https://cs.nyu.edu/~panozzo/cg17/Slides/10%20-%20Texture%20Mapping.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/cg17/Slides/10%20-%20Texture%20Mapping.key.zip)
* 11/27: [11 - Spatial Data Structures](https://cs.nyu.edu/~panozzo/cg17/Slides/11%20-%20Spatial%20Data%20Structures.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/cg17/Slides/11%20-%20Spatial%20Data%20Structures.key.zip)
* 12/04: [12 - Spatial and Skeletan Deformations](https://cs.nyu.edu/~panozzo/cg17/Slides/12%20-%20Spatial%20and%20Skeletal%20Deformations.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/cg17/Slides/12%20-%20Spatial%20and%20Skeletal%20Deformations.key.zip)
* 12/11: [13 - Mesh Data Structures](https://cs.nyu.edu/~panozzo/cg17/Slides/13%20-%20Meshes.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/cg17/Slides/13%20-%20Meshes.key.zip)
* 12/12: 14 - Open Q&A for the projects and final exam
* 12/18: 15 - FINALS and project presentation

## Assignments

* [General guidelines](http://cs.nyu.edu/~panozzo/cg17/Assignments/0%20-%20General%20Rules.pdf) [(latex)](http://cs.nyu.edu/~panozzo/cg17/Assignments/0%20-%20General%20Rules.zip)

* [Assignment 1: Ray tracing](Assignment_1/requirements/Assignment-1_Ray_Tracing.pdf) [(latex)](Assignment_1/requirements/Assignment-1_Ray_Tracing.tex)

* [Assignment 2: 2D Vector graphics editor](Assignment_2/requirements/Assignment-2_2D_Editor.pdf) [(latex)](Assignment_2/requirements/Assignment-2_2D_Editor.tex)

* [Assignment 3: 3D Scene Editor](Assignment_3/requirements/Assignment3_3D.pdf)

* [Assignment 4: Final Project](Assignment_4/requirements/Assignment4.pdf)

# Compilation Instructions

```bash
git clone --recursive https://github.com/NYUCG2017/assignment-N-username # --recursive flag is necessary for dependencies
cd assignment-N-username
mkdir build
cd build
cmake ../ # re-run cmake when you add/delete source files
make
```
You can substitute `cmake ../` with the following to make the program run faster
```bash
cmake -DCMAKE_BUILD_TYPE=Release ../ # use this cmake command instead of the previous linefor faster run
```

If you are looking for an IDE, I suggest to use [CLion](https://www.jetbrains.com/clion/) or [VSCode](https://code.visualstudio.com).
