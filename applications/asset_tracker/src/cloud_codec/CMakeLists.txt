#
# Copyright (c) 2019 Nordic Semiconductor
#
# SPDX-License-Identifier: LicenseRef-Nordic-5-Clause
#

zephyr_include_directories(.)
target_sources(app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/cloud_codec.c)
target_sources(app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/service_info.c)
