project(Gajiwo)
file(GLOB SOURCES "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp")
add_library(libun SHARED ${SOURCES})
target_include_directories(libun PUBLIC ${CMAKE_SOURCE_DIR}/include)