## Dataset Structure

### Subject Level
The subject folder P1-P15 (except P9) represents the data of 14 participants

### Activity Level
In each subject folder, there are 9 activity folders, including 6 fall activities (F1-F6) and 3 fall-like activities (FL1-FL3). The corresponding activity description can be found [here](../README.md).

### csv file structure
In each activity folder, there are several .csv files that represent the trials of this activity.  

For each .csv file, 9 IMUs' sensing data with 15 Hz are stored. The data include the raw data of the triaxial accelerometer, gyroscope, and magnetometer, and also the computed quaternion values using the Mahony AHRS method.

Particularly, for the Node 0-8, the corresponding positions are:
|Node|Postion|
|----|-------|
| 0 | Back |
| 1 | Right upper arm |
| 2 | Right wrist |
| 3 | Left upper arm |
| 4 | Left wrist |
| 5 | Left thigh |
| 6 | Left ankle |
| 7 | Right thigh |
| 8 | Right ankle |

### Manually labelling the falling period
[label.csv](/fall_dataset/label.csv) represents the 5 phases of the fall by further separating the activity based on recorded videos, including before falling (0-T1), pre-impact (T1-T2), impacted (T2-T3), post-impacted (T3-T4), get up (T4-end). 
