cmake_minimum_required(VERSION 3.17)
project(imgui)

set(CMAKE_CXX_STANDARD 17)

# Create library
add_library(${PROJECT_NAME} STATIC
        imconfig.h
        imgui.h
        imgui.cpp
        imgui_draw.cpp
        imgui_internal.h
        imgui_widgets.cpp
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h
        imgui_demo.cpp
        )
