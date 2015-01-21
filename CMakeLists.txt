cmake_minimum_required(VERSION 2.6.2)

include(ReMake)

remake_project(
  blender-urdf
  VERSION 0.1
  RELEASE beta
  SUMMARY "Unified Robot Description Format (URDF) import-export addon for Blender."
  AUTHOR "Ralf Kaestner"
  CONTACT "ralf.kaestner@gmail.com"
  HOME "http://github.com/kralf/blender-urdf"
  LICENSE "GNU Lesser General Public License (LGPL)"
  INSTALL /usr
)
