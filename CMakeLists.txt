# Copyright (c) 2026 The ZMK Contributors
# SPDX-License-Identifier: MIT

target_sources_ifdef(CONFIG_LINEA40_BATTERY_TEXT app PRIVATE src/behavior_battery_text.c)
target_sources_ifdef(CONFIG_LINEA40_INERTIAL_SCROLL app PRIVATE src/input_processor_inertial_scroll.c)
