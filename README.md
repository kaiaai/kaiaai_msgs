# Kaia.ai platform ROS2 messages

[Kaia.ai](https://kaia.ai) is a platform for 3D-printed pet robots. Please sign up for an early launch invite [here](https://kaia.ai).

## Change Log

### v0.2.0 - in debug
- added KaiaTelemetry2 message
  - adds wifi_rssi, battery_mv, distance_mm[], bumper[], cliff[], touch[]

### v0.1.0
- initial release
  - odometry position, yaw, velocity
  - joint positions, velocity
  - raw LiDAR/LDS laser distance scan data stream
