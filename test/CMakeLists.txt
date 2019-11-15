add_executable(conway_test
    test_conway.cpp
    test_main.cpp
)

target_link_libraries(conway_test PRIVATE conway)

add_test(conway_test conway_test)