set(EXECUTABLE_OUTPUT_PATH ${TOPDIR}/out)
set(LIBRARY_OUTPUT_PATH ${TOPDIR}/out)


include_directories(
        ${TOPDIR}/src
)

add_executable(test_h264bsd test_h264bsd.c)

target_link_libraries(test_h264bsd h264bsd)
