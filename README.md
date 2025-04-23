Type the following command to build the image file:
```
cmake --build build --config release
```

Then use the following command to run the program in order to get the image in ppm format:
```
./build/Release/ray_tracing.exe > image.ppm
```