# Copyright (c) 2023 Deimantas Aukštkalnis 
# SPDX-License-Identifier: Apache-2.0

message("+++++++++++++++++++++ enetering success")

add_subdirectory_ifdef(CONFIG_HAS_BLUENRG_LIB soc)
