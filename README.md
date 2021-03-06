# nonpersistent_voxel_layer
ROS drop in replacement to the voxel layer which does not persist readings through iterations when ray tracing or map maintenance is undesirable.

 * AMD64 Debian Job Status: [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__navigation__ubuntu_xenial_amd64__binary)](http://build.ros.org/job/Kdev__nonpersistent_voxel_layer__ubuntu_xenial_amd64/2/)

Created in response to need for a rolling local costmap layer to not persist readings due to a specific sensor being used. After looking through the community, it seems several people on ros answers have asked for a similar tool. This is to make that possible. 

I chose not to modify the ROS navigation voxel layer directly since development has moved to Lunar and my stacks are still on Kinetic.

Build and tested on ROS1 Kinetic, verified working in Indigo.
