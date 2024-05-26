project(glad)

add_library(glad include/glad/glad.h src/glad.c)

target_include_directories(glad PUBLIC ${CMAKE_SOURCE_DIR}/third_party/glbasics_third_party/glad/include)