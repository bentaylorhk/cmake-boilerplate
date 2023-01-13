# Benjamin Michael Taylor (bentaylorhk)
# 2023

file (GLOB_RECURSE SOURCES CONFIGURE_DEPENDS ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp)

create_target(
        NAME "sample"
        SOURCES ${SOURCES}
        EXECUTABLE
)