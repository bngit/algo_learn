cmake_minimum_required(VERSION 3.5)

project (algo_learn)

# set the C++ standard to C++ 14
set(CMAKE_CXX_STANDARD 14)

add_executable(algo_learn
    main.cpp
    sort/sort.cpp
)

target_include_directories(algo_learn
    PRIVATE
        ${PROJECT_SOURCE_DIR}/sort
)
