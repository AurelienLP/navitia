add_library(equipment_api equipment_api.cpp)
add_dependencies(equipment_api protobuf_files)
add_subdirectory(tests)
