cmake_minimum_required(VERSION 3.5)

project(foobar)

add_library(foobar INTERFACE)

message("LLVM_DIR=" ${LLVM_DIR})
message("LLVM_LIB_DIR=" ${LLVM_LIB_DIR})
message("LLVM_INCLUDE_DIRS=" ${LLVM_INCLUDE_DIRS})
message("LLVM_LIBS=" ${LLVM_LIBS})
message("LLVM_DEFINITIONS=" ${LLVM_DEFINITIONS})
message("LLVM_LD_FLAGS=" ${LLVM_LD_FLAGS})
message("LLVM=" ${LLVM})
message("BUILD_HTTP_STATIC=" ${BUILD_HTTP_STATIC})
message("USE_STATIC_SNDFILE=" ${USE_STATIC_SNDFILE})
message("CMAKEOPT=" ${CMAKEOPT})
message("INCLUDE_LLVM=" ${INCLUDE_LLVM})
message("USE_LLVM_CONFIG=" ${USE_LLVM_CONFIG})