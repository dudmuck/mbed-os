# Copyright (c) 2020 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

if("ARM_FM" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_ARM_FM)
elseif("Cypress" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_Cypress)
elseif("Freescale" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_Freescale)
elseif("GigaDevice" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_GigaDevice)
elseif("Maxim" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_Maxim)
elseif("NORDIC" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_NORDIC)
elseif("NUVOTON" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_NUVOTON)
elseif("NXP" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_NXP)
elseif("Silicon_Labs" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_Silicon_Labs)
elseif("STM" IN_LIST MBED_TARGET_LABELS)
    add_subdirectory(TARGET_STM)
endif()
