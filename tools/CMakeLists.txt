add_executable(unibi-dump unibi-dump.c)
target_link_libraries(unibi-dump unibilium)
target_include_directories(unibi-dump PRIVATE ${PROJECT_SOURCE_DIR})

add_executable(unibi-put unibi-put.c)
target_link_libraries(unibi-put unibilium)
target_include_directories(unibi-put PRIVATE ${PROJECT_SOURCE_DIR})

add_executable(gen-static-test gen-static-test.c)
target_link_libraries(gen-static-test unibilium)
target_include_directories(gen-static-test PRIVATE ${PROJECT_SOURCE_DIR})
