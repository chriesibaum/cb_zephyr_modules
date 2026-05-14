# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20)

if(CONFIG_CB_ZEPHYR_MODULE)
  add_subdirectory(drivers)
  add_subdirectory(lib)
endif()
