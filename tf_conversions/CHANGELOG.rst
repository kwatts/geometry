^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package tf_conversions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.10.7 (2013-12-27)
-------------------
* Fix build error in tf_conversions with orocos_kdl dependency
  Fixes `#45 <https://github.com/ros/geometry/issues/45>`_
* Contributors: Tessa Lau

1.10.6 (2013-08-28)
-------------------

1.10.5 (2013-07-19)
-------------------

1.10.4 (2013-07-11)
-------------------

1.10.3 (2013-07-09)
-------------------
* calling out versioned catkin requirement for CATKIN_ENABLE_TESTING

1.10.2 (2013-07-09)
-------------------
* adding unit test if CATKIN_ENABLE_TESTING statements for tf_conversions to make the whole repo compliant.

1.10.1 (2013-07-05)
-------------------

1.10.0 (2013-07-05)
-------------------
* fixing unit tests
* fixing kdl linking

1.9.31 (2013-04-18 18:16)
-------------------------

1.9.30 (2013-04-18 16:26)
-------------------------

1.9.29 (2013-01-13)
-------------------

1.9.28 (2013-01-02)
-------------------
* add missing setup.py

1.9.27 (2012-12-21)
-------------------
* added license headers to various files

1.9.26 (2012-12-14)
-------------------
* add missing dep to catkin

1.9.25 (2012-12-13)
-------------------

1.9.24 (2012-12-11)
-------------------
* Version 1.9.24
* Fixes to CMakeLists.txt's while building from source

1.9.23 (2012-11-22)
-------------------
* Releaseing version 1.9.23

1.9.22 (2012-11-04 09:14)
-------------------------
* more backwards compatible conversions and an include to make sure it gets into the old header location

1.9.21 (2012-11-04 01:19)
-------------------------
* filling out deprecated functions for backwards compatability

1.9.20 (2012-11-02)
-------------------

1.9.19 (2012-10-31)
-------------------
* Removed deprecated 'brief' attribute from <description> tags.

1.9.18 (2012-10-16)
-------------------

1.9.17 (2012-10-02)
-------------------
* fix several dependency issues

1.9.16 (2012-09-29)
-------------------
* adding geometry metapackage and updating to 1.9.16

1.9.15 (2012-09-30)
-------------------
* fix a few dependency/catkin problems
* remove old API files
* comply to the new catkin API

1.9.14 (2012-09-18)
-------------------

1.9.13 (2012-09-17)
-------------------
* update manifests

1.9.12 (2012-09-16)
-------------------

1.9.11 (2012-09-14 22:49)
-------------------------

1.9.10 (2012-09-14 22:30)
-------------------------

1.9.9 (2012-09-11)
------------------
* update depends
* minor patches for new build system

1.9.8 (2012-09-03)
------------------

1.9.7 (2012-08-10 12:19)
------------------------
* minor build fixes
* fixed some minor errors from last commit
* completed set of eigen conversions; added KDL conversions
* adding additional conversion functions

1.9.6 (2012-08-02 19:59)
------------------------

1.9.5 (2012-08-02 19:48)
------------------------

1.9.4 (2012-08-02 18:29)
------------------------

1.9.3 (2012-08-02 18:28)
------------------------
* forgot to install some things
* also using DEPENDS

1.9.2 (2012-08-01 21:05)
------------------------
* make sure the tf target depends on the messages (and clean some include_directories too)

1.9.1 (2012-08-01 19:16)
------------------------
* install manifest.xml

1.9.0 (2012-08-01 18:52)
------------------------
* catkin build system
* successfully running rosrun tf bullet_migration_sed.py and testing afterwords
* eigen to rosdep from dependency
* removing eigen dependency as it's now system installed
* add missing empty_listener.cpp file
* compiling with eigen3
* more extensive search
* applying patch from sed script for eigen3 compatability
* tests for tf_kdl and fixes for tf_kdl based on tests
* add pykdl to example
* link to kdl pages
* Added VectorEigenToTF and RotationEigenToTF to tf_conversions
* returning to camelCase for consistency with tf and pykdl
* converting from camelCase to under_scored methods for python style
* Added Ubuntu platform tags
* removing pykdl finishing series of commits for `#4039 <https://github.com/ros/geometry/issues/4039>`_
* promoting pykdl index.rst
* removing index.rst for replacing
* posemath using kdl promoted
* reverting change in test
* passing test with kdl_posemath.py copied to src/posemath.py
* Corrected module to tf_conversions
* Improved pose comparison in test_roundtrip
* `#4039 <https://github.com/ros/geometry/issues/4039>`_ original posemath now in tf_conversions
* Enable posemath unit test, `#4039 <https://github.com/ros/geometry/issues/4039>`_
* Moved PoseMath from tf to tf_conversions, `#4039 <https://github.com/ros/geometry/issues/4039>`_
* PyKDL based PoseMath, `#4039 <https://github.com/ros/geometry/issues/4039>`_
* fixes for `#3915 <https://github.com/ros/geometry/issues/3915>`_ into trunk
* Remove use of deprecated rosbuild macros
* tf conversions is doc reviewed
* api cleared
* add list of supported data types
* deprecate addDelta function because it is not a conversion
* add api doc to tf_conversions
* update documentation
* migration part 1
