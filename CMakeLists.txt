cmake_minimum_required(VERSION 3.5)

project(foobar)

add_library(foobar INTERFACE)

message(${LLVM_DIR})
message(${LLVM_LIB_DIR})
message(${LLVM_INCLUDE_DIRS})
message(${LLVM_LIBS})
message(${LLVM_DEFINITIONS})
message(${LLVM_LD_FLAGS})
message(${LLVM})
message(${BUILD_HTTP_STATIC})
message(${USE_STATIC_SNDFILE})
message(${CMAKEOPT})
message(${INCLUDE_LLVM})
message(${USE_LLVM_CONFI})