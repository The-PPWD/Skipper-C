add_executable(
    skipperctest
    test.c
)

target_link_libraries(
    skipperctest
    PRIVATE
    skipperc
)

add_test(
    NAME skipperctest
    COMMAND skipperctest
)
