cmake_minimum_required(VERSION 3.5)

list(APPEND EXTRA_COMPONENT_DIRS ../../components  $ENV{IDF_PATH}/examples/common_components/protocol_examples_common)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(file_server_stm)
