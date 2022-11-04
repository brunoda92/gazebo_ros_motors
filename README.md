# Gazebo ROS motor plugins

This repository is a fork from nilseuropa's original [plugin](https://github.com/nilseuropa/gazebo_ros_motors), which I modified in order to ignore motor's current dynamic. Also, it doesn't model the *load* of the motor, trusting that task to Gazebo: just calculate torque from voltage input and load speed and apply torque to object through Gazebo.

# More detail here

##### Authors

Bruno D'Angelo [brunoda92](https://github.com/brunoda92) in cooperation with Sebastián Sansoni
