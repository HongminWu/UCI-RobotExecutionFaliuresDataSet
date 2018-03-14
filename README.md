The source was built in [UCI](https://archive.ics.uci.edu/ml/datasets/Robot+Execution+Failures)
### Abstract:
This dataset contains wrench (6D: force and torque) measurements on a robot after failure detection. Each failure is characterized by 15 force/torque samples collected at regular time intervals
###Data Set Information:
The donation includes 5 datasets, each of them defining a different learning problem:
* LP1: failures in approach to grasp position
* LP2: failures in transfer of a part
* LP3: position of part after a transfer failure
* LP4: failures in approach to ungrasp position
* LP5: failures in motion with part
### INFO
All features are numeric although they are integer valued only. Each feature represents a force or a torque measured after failure detection; each failure instance is characterized in terms of 15 force/torque samples collected at regular time intervals starting immediately after failure detection; The total observation window for each failure instance was of 315 ms.

Each example is described as follows:

class
Fx1 Fy1 Fz1 Tx1 Ty1 Tz1
Fx2 Fy2 Fz2 Tx2 Ty2 Tz2
......
Fx15 Fy15 Fz15 Tx15 Ty15 Tz15

where Fx1 ... Fx15 is the evolution of force Fx in the observation window, the same for Fy, Fz and the torques; there is a total of 90 features. 