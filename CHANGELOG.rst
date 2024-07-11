^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hippo_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* moved acoustic related msgs to acoustic_msgs
* removed estimator msgs
* add BoolStamped
* migrated to hippo_control_msgs
* fixed warning related to xml schema
* change type in AnchorPose
* add anchor poses msgs
* Niklas' changes squashed
* added comment for non physical setpoints
* snapshot for paper
* added control mode message for motor failure controller
* added debug msg for path follower
* added debug messages
* added licenses and applied formatting to all source files
* added possibly missing msg dependencies
* change distance fields name
* use standard header instead of time
* add ModemOut.msg for acoustic simulator
* path planning package added
* Merge pull request `#13 <https://github.com/HippoCampusRobotics/hippo_msgs/issues/13>`_ from niklastkl/merge_to_upstream
  Add conversion utilities Eigen Ref
* added DepthStamped-msg, names of message components up to discussion, so far old ones
* commit before upstream pull request
* Merge remote-tracking branch 'upstream/main'
* added newton gripper message
* Added convertion util functions for Eigen Reference type
* added control target msg type
* range_sensor framework
* separate pkg for protobuf msgs
* debug msgs
* avoid divergence
* more debug messages
* added compiler optimizations
* new messages for better mixing
* added new messages
* added force publisher for the thruster plugin
  Also renamed input topic to throttle_cmd because this is the better term
* added cmake definition for clang-tidy
* added compiler flags
* initial commit
* Contributors: NBauschmann, Niklas T, Thies Lennart Alff, niklastkl
