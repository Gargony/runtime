set(SOURCES
  sleep.cpp
)

add_executable(paltest_sleep_test2
  ${SOURCES}
)

add_dependencies(paltest_sleep_test2 coreclrpal)

target_link_libraries(paltest_sleep_test2
  ${COMMON_TEST_LIBRARIES}
)
