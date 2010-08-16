# Copyright (c) 2010 Daniel Pfeifer <daniel@pfeifer-mail.de>

cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Maoni-Slides)

include(${CMAKE_SOURCE_DIR}/UseLATEX.cmake)

add_latex_document(slides.tex
  IMAGE_DIRS images
  )
