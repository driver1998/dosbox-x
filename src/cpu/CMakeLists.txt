set(SRC_CPU
	"${CMAKE_CURRENT_LIST_DIR}/callback.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/CMakeLists.txt"
	"${CMAKE_CURRENT_LIST_DIR}/core_dyn_x86.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/core_full.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/core_normal.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/core_normal_286.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/core_normal_8086.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/core_prefetch.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/core_simple.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/cpu.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/flags.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/instructions.h"
	"${CMAKE_CURRENT_LIST_DIR}/lazyflags.h"
	# "${CMAKE_CURRENT_LIST_DIR}/Makefile.am"
	"${CMAKE_CURRENT_LIST_DIR}/mmx.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/modrm.cpp"
	"${CMAKE_CURRENT_LIST_DIR}/modrm.h"
	"${CMAKE_CURRENT_LIST_DIR}/paging.cpp"
)
source_group("Sources\\cpu" FILES ${SRC_CPU})
