file(GLOB_RECURSE SOURCES ./*.c)
add_library(lv_drivers_fb STATIC ${SOURCES})
