cmake_minimum_required(VERSION 3.20)

project(oop_mai_labs)

include(cmake/RequersOptions.cmake)

include(FetchContent)
FetchContent_Declare(
        googletest
        GIT_REPOSITORY https://github.com/google/googletest.git
        GIT_TAG f8d7d77
)
FetchContent_MakeAvailable(googletest)


add_subdirectory(labs)
