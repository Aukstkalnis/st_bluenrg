# Copyright (c) 2023 Deimantas Aukštkalnis
# SPDX-License-Identifier: Apache-2.0

zephyr_library()

message("888888888888888888 OK 1")

if(CONFIG_SOC_SERIES_BLUENRG2)
	message("8888888888888888 OK")
	zephyr_include_directories(BlueNRG2)
endif()
