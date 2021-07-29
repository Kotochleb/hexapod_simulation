# Robot model
URDF model was written using Xacro with ability to be reconfigured for other hexapods using `props.yaml`. 3d model was designed in Solidworks and than exported to fit Gazebo requirements.

# Running simulation
* `twt_display.launch` launches Rviz with `joint_state_publisher` with qui as default.
* `twt_simulation.launch` launches Gazebo simulation.
