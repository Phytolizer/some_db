cmake_minimum_required(VERSION 3.12...3.22)
project(
    "some_db"
    VERSION "0.1.0"
    LANGUAGES "C"
    DESCRIPTION "A database or something"
    HOMEPAGE_URL "https://github.com/Phytolizer/some_db"
)

set(CMAKE_C_STANDARD 11)

add_executable(
    "some_db"
    "src/main.c"
)
