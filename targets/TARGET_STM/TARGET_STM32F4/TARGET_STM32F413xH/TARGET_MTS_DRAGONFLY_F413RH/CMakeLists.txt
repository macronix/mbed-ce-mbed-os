# Copyright (c) 2021 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

add_library(mbed-mts-dragonfly-f413rh INTERFACE)

target_sources(mbed-mts-dragonfly-f413rh
    INTERFACE
        PeripheralPins.c
)

target_include_directories(mbed-mts-dragonfly-f413rh
    INTERFACE
        .
)

target_link_libraries(mbed-mts-dragonfly-f413rh INTERFACE mbed-stm32f413xh)
