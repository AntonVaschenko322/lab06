add_library(formatter_ex_lib STATIC formatter_ex.cpp) 
target_include_directories(formatter_ex_lib PUBLIC include formatter_lib.h formatter_ex_lib.h)
target_link_libraries(formatter_ex_lib PRIVATE formatter_lib)    
