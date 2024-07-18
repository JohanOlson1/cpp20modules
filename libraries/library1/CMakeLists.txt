file(GLOB SRC_FILES src/*.cc)

add_library(library1)# STATIC ${SRC_FILES})

target_sources(
	library1
	PUBLIC
	FILE_SET CXX_MODULES FILES
	src/test.cc	
)

target_link_libraries(
	library1
	PUBLIC
	IPP::ippcore IPP::ipps
)
