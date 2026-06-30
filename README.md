# RoboticsTutorial
Notebook for Full-stack Robotics

## Create Python Virtual Environment
python3 -m venv venv
source venv/bin/activate

# Create a python executable wrapper named `python-ros` in the venv/bin directory

```bash
#!/bin/bash
# Source the ROS environment
source /opt/ros/kilted/setup.bash

# Execute the python executable with the passed arguments
exec /home/anurag/Documents/NextAISenseRepo/RoboticsTutorial/venv/bin/python "$@"
```