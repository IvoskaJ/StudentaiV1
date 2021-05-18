# CMakeList.txt : CMake project for student v1.0, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("student v1.0")

set(CMAKE_CXX_FLAGS_RELEASE: -O3 -DNDEBUG)

# Add source to this project's executable.
add_executable (generateFiles "generateFiles.cpp" "Studentas.h")
add_executable (vector_class  "vector1class.cpp"  "vector1class.h" "StudentasClass.h" )
add_executable (vector_struct   "vector1struct.cpp"  "vector1struct.h" "Studentas.h" )

# TODO: Add tests and install targets if needed.
