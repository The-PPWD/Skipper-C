add_library(
    skipperc
    constants/pi.c
)

target_include_directories(
    skipperc
    PUBLIC
    ${PROJECT_SOURCE_DIR}/include
)
