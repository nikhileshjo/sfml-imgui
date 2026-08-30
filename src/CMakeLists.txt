add_executable(example_exe main.cpp)

target_include_directories(example_exe PRIVATE
    ${imgui_SOURCE_DIR}
)



target_link_libraries(example_exe PRIVATE
    ImGui-SFML
)