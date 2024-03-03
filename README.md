# Kaia.ai platform ROS2 messages

[Kaia.ai](https://kaia.ai) is a platform for 3D-printed pet robots. Please sign up for an early launch invite [here](https://kaia.ai).

## Change Log

### v0.2.0 - in debug
- added JointPosVel message
- added KaiaTelemetry2 message
  - adds wifi_rssi_dbm, battery_mv, distance_mm[], bumper[], cliff[], touch[]
  - adds scan_start_hint
  - limits array lengths
  - change joint_pos[], joint_vel[] to JointPosVel[]
- added WifiState message

### v0.1.0
- initial release
  - odometry position, yaw, velocity
  - joint positions, velocity
  - raw LiDAR/LDS laser distance scan data stream
