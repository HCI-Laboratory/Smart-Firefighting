## Dataset Structure

### Subject Level
The subject folder Subject_01-Subject_18 represents the data of 18 participants

### Activity Level
In each subject folder, there are 8 activity folders, Activity_01-Activity_08. The corresponding activity description can be found [here](../README.md).

### Segment Level
In each Activity folder, there are several Segment folders representing trials of this activity during the training. Each segment is manually split by comparing the recorded videos.

### csv file structure
In each Segment folder, there are 5 .csv files where Body, LA, LS, RA, and RS represent the positions of sensor nodes, corresponding to the back, left arm, left shank, right arm, and right shank.

The sensing data are the same for LA, LS, RA, and RS, including Timestamp (in second), triaxial accelerometer data (Ax, Ay, Az), triaxial gyroscope data (Rx, Ry, Rz), and sEMG signals (EMG).

Whilst, for the Body.csv file, the column of sEMG signals is replaced by the Heart Rate (HR).
