cmake_minimum_required(VERSION 3.10)
project(videoPlayer_ffmpeg_sdl)

set(CMAKE_CXX_STANDARD 14)
add_executable(videoPlayer_ffmpeg_sdl main.cpp)
target_link_libraries(videoPlayer_ffmpeg_sdl avformat avcodec avutil swscale)
target_link_libraries(videoPlayer_ffmpeg_sdl SDL2)