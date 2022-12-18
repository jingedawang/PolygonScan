project(PolygonScan)

add_compile_options(-std=c++11)

add_executable(PolygonScan main.cpp)

target_link_libraries(PolygonScan GL)
target_link_libraries(PolygonScan GLU)
target_link_libraries(PolygonScan glut)