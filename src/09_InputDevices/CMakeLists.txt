cmake_minimum_required (VERSION 3.8)

set(CMAKE_CONFIGURATION_TYPES "Debug;Release" CACHE STRING "" FORCE)
set(CMAKE_SUPPRESS_REGENERATION true)

add_subdirectory( BakudanBitoWithJoystick )
add_subdirectory( Joystick )
add_subdirectory( Keyboard )
add_subdirectory( Mouse )
