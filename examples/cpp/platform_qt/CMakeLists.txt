# Copyright © SixtyFPS GmbH <info@slint.dev>
# SPDX-License-Identifier: MIT

add_executable(platform_qt main.cpp)
target_link_libraries(platform_qt PRIVATE Slint::Slint Qt::Gui Qt::Widgets Qt::GuiPrivate)
slint_target_sources(platform_qt app-window.slint)

