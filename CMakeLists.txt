cmake_minimum_required(VERSION 3.6)
project(BufMgr)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
add_custom_target(BufMgr COMMAND make -C ${BufMgr_SOURCE_DIR}
        CLION_EXE_DIR=${PROJECT_BINARY_DIR})
#add_executable(BufMgr ${SOURCE_FILES})