cmake_minimum_required(VERSION 2.8.3)
project(neato_2dnav)

find_package(catkin REQUIRED)
catkin_package(DEPENDS)

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

<<<<<<< HEAD
=======
install(DIRECTORY maps
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

>>>>>>> 1fcf04fd660ea6d819d783bfc0f4a6018b0fafb7
install(DIRECTORY params
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
