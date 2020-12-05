cmake_minimum_required(VERSION 3.19)

project(jgameboy
  VERSION 0.0.1
  DESCRIPTION "A gameboy emulator"
  HOMEPAGE_URL "https://github.com/jcomans/jgameboy"
  LANGUAGES CXX
  )

add_executable(jgameboy
  source/main.cpp
  )
