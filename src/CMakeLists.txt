set(NAME compiler)

file(GLOB_RECURSE SRC
	"*.cpp"
	"*.c"
)

add_library(${NAME}
	SHARED
	${SRC}
)

#target_link_libraries(${NAME}
#	${_LIBS}
#)