
qt_add_library(PositionManager STATIC
	PositionManager.cpp
	SimulatedPosition.cc
)

target_link_libraries(PositionManager
	PUBLIC
		qgc
)

target_include_directories(PositionManager
	PUBLIC
		${CMAKE_CURRENT_SOURCE_DIR}
	)

