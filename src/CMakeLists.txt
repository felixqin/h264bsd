
add_definitions(-D_ASSERT_USED -D_DEBUG_PRINT -D_ERROR_PRINT)

aux_source_directory(. SRCS)

add_library(h264bsd
        ${SRCS}
        )

