# The following lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)

#set (EXTRA_COMPONENT_DIRS "./../../.")
#set (EXTRA_COMPONENT_DIRS "../../esp/Samples/extra_components")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(shoalboard_test_master)
