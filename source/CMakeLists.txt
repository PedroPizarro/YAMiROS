target_sources(${PROJECT_NAME}
    PRIVATE
    kernel/kernel.cpp)

target_include_directories(${PROJECT_NAME} 
    PUBLIC
    ../include    
)