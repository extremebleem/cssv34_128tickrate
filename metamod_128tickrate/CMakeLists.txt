# CMakeList.txt: проект CMake для metamod_128tickrate; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#

# Добавьте источник в исполняемый файл этого проекта.
add_executable (metamod_128tickrate "metamod_128tickrate.cpp" "metamod_128tickrate.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET metamod_128tickrate PROPERTY CXX_STANDARD 20)
endif()

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
