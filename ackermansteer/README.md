# ackermansteer



### Notes to self / Learnings:
* SetPosition worked abysmally to set wheel angles. I'm assuming because the resulting discontinuity requires temporary interuption of the simulation... not sure need to research.
* Ackermann is actually spelled with 2 n's.
* PID controller is good for setting forces on wheels (runs much smoother). Not sure though if this is the current 'best practice' for setting the joint angles as I understand the joints have embedded PID controllers... but havent found the documetnation on these yet.
* For some reason, specifiying gazebo in makefile as a catkin component does not work. Need to find_package separately, and include/link separately as well. 