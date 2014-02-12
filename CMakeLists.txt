cmake_minimum_required(VERSION 2.8.7 FATAL_ERROR)

set(CPM_MODULE_NAME sine.core)

# initialize
if(NOT EXISTS ${CMAKE_CURRENT_BINARY_DIR}/init.cmake)
  file(DOWNLOAD https://raw.github.com/toeb/cpm/master/init-cpm.cmake ${CMAKE_CURRENT_BINARY_DIR}/init.cmake)
endif()
include(${CMAKE_CURRENT_BINARY_DIR}/init.cmake)


message("success!")
