# Kaia.ai platform ROS2 messages

Abbreviated telemetry messages for [Kaia.ai](https://kaia.ai) home robot software platform.

Please sign up for an early launch invite [here](https://kaia.ai).

## Change Log

### v0.2.0 - in debug
- added WifiState message for ROS2
- added KaiaTelemetry2 message
  - added JointPosVel message
  - adds wifi_rssi_dbm, battery_mv, distance_mm[], bumper[], cliff[], touch[]
  - adds scan_start_hint
  - limits array lengths
  - change joint_pos[], joint_vel[] to JointPosVel[]
- added WifiState message
- limited array lengths for compact message size

### v0.1.0
- initial release
  - odometry position, yaw, velocity
  - joint positions, velocity
  - raw LiDAR/LDS laser distance scan data stream
