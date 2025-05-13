cmake_minimum_required(VERSION 3.15)

if(ESP_PLATFORM)
	idf_component_register(INCLUDE_DIRS src)
	return()
endif()

project(PNGdec VERSION 1.0.1)
add_subdirectory(src)
