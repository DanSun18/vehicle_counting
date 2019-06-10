add_executable(vehicle_counting_demo Blob.cpp
Blob.h
Main.cpp
)

target_link_libraries( vehicle_counting_demo ${OpenCV_LIBS} )
     
install (TARGETS vehicle_counting_demo DESTINATION bin)
