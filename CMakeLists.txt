cmake_minimum_required(VERSION 3.27)
project(ray_tracing)

set(CMAKE_CXX_STANDARD 17)

add_executable(
        ray_tracing main.cc
        vec3.h
        color.h
        ray.h
        hittable.h
        sphere.h
        hittable_list.h
        ray_tracing.h
)
