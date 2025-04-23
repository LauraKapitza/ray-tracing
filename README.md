# Ray Tracing Project

## Introduction
This is a follow-along project to build a small ray tracer in C++ based on [this tutorial](https://raytracing.github.io/books/RayTracingInOneWeekend.html).


## Run the program

Type the following command to build the image file:
```
cmake --build build --config release
```

Then use the following command to run the program in order to get the image in ppm format:
```
./build/Release/ray_tracing.exe > image.ppm
```