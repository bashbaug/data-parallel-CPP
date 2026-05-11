# Copyright (C) 2023 Intel Corporation

# SPDX-License-Identifier: MIT

add_book_sample(
    TEST
    TARGET fig_16_6_stream_triad
    SOURCES fig_16_6_stream_triad.cpp)

if(NOT EXTRASKIP)
add_book_sample(
    TEST
    TARGET fig_16_12_forward_dep  
    SOURCES fig_16_12_forward_dep.cpp)
endif()

add_book_sample(
    TEST
    TARGET fig_16_18_vector_swizzle  
    SOURCES fig_16_18_vector_swizzle.cpp)
