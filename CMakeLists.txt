# CMakeList.txt : CMake project for student v1.0, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("student v1.0")

# Add source to this project's executable.
add_executable (generateFiles "generateFiles.cpp" "Studentas.h")
add_executable (vector_class  "vector1class.cpp"  "vector1class.h" "StudentasClass.h" )

# TODO: Add tests and install targets if needed.
