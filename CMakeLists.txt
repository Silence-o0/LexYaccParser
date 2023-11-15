cmake_minimum_required(VERSION 3.26)
project(LexYaccParser)

set(CMAKE_CXX_STANDARD 20)

add_executable(LexYaccParser
        lex.yy.c
        yacc.tab.c
)

target_link_libraries(LexYaccParser C:/GnuWin32/lib/libfl.a)