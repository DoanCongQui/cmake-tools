# Cmake opencv
Build opencv & create file `CMakeList.txt` on project

`CMakeList.txt`
```
cmake_minimum_required(VERSION 3.10)
project(<Name Project>)

find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(main <name_file_main>)
target_link_libraries(main ${OpenCV_LIBS})

```
