# Copyright (c) 2017, United States Government, as represented by the
# Administrator of the National Aeronautics and Space Administration.
#
# All rights reserved.
#
# The Astrobee platform is licensed under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with the
# License. You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
# WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
# License for the specific language governing permissions and limitations
# under the License.

cmake_minimum_required(VERSION 3.5)
project(astrobee_handrail_30)

# Find amend and libraries
find_package(ament_cmake REQUIRED)

#############
## Install ##
#############

ament_environment_hooks("${CMAKE_CURRENT_SOURCE_DIR}/env-hooks/${PROJECT_NAME}.dsv.in")

install(DIRECTORY urdf DESTINATION share/${PROJECT_NAME})
install(DIRECTORY media DESTINATION share/${PROJECT_NAME})
install(DIRECTORY meshes DESTINATION share/${PROJECT_NAME})

install(PROGRAMS model.config DESTINATION share/${PROJECT_NAME})
install(PROGRAMS model.config DESTINATION share/colcon-core)
install(PROGRAMS model.config DESTINATION share/ament_index)

ament_package()