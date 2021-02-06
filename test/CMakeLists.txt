add_executable(
    skipperctest
    constants/pi.c
)

target_link_libraries(
    skipperctest
    PRIVATE
    skipperc
)
