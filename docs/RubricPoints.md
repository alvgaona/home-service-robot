# Project Specifications
## Home Robot Service

### Basic Requirements

| CRITERIA |  MEETS SPECIFICATIONS |
|----------|-----------------------|
| Did the student submit all required files? | Student submitted all required files: ROS Packages, Shell scripts |

### Simulation Setup

| CRITERIA |  MEETS SPECIFICATIONS |
|----------|-----------------------|
| Did the student set up the simulation environment properly? | Student's simulation world and robot could properly load in Gazebo. |

### Mapping

| CRITERIA |  MEETS SPECIFICATIONS |
|----------|-----------------------|
| Did the student's mapping function work properly? | The student should write a test_slam.sh script file and launch it to manually test SLAM. |
| Did the student create a map using SLAM? | Student created a functional map of the environment which would be used for localization and navigation tasks. |

### Localization and Navigation

| CRITERIA |  MEETS SPECIFICATIONS |
|----------|-----------------------|
| Was the student's navigation stack configured properly? | The student's robot could navigate in the environment after a 2D Nav Goal command is issued. The student created a test_navigation.sh script file to launch it for manual navigation test. |
| Did the student's goal node function properly? | "The student created a pick_objects.sh file that will send multiple goals for the robot to reach. The robot travels to the desired pickup zone, displays a message that it reached its destination, waits 5 seconds, travels to the desired drop off zone, and displays a message that it reached the drop off zone." |

### Home Service Functions

| CRITERIA |  MEETS SPECIFICATIONS |
|----------|-----------------------|
| Did the student create virtual object with markers? | The student should write a add_marker.sh file that will publish a marker to rviz. The marker should initially be published at the pickup zone. After 5 seconds it should be hidden. Then after another 5 seconds it should appear at the drop off zone. |
| Does the student's robot perform home service tasks correctly? | The student should write a home_service.sh file that will run all the nodes in this project. The student's home service robot should be simulated as follow: Initially show the marker at the pickup zone, hide the marker once your robot reach the pickup zone, wait 5 seconds to simulate a pickup, show the marker at the drop off zone once your robot reaches it. |
| Did the student include a write-up explaining the packages used to achieve home service functionalities? | The student should include a brief write-up explaining the packages used for this project, covering localization, mapping and navigation. |                                              
