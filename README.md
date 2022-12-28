# Walking-Speed-Estimation-with-an-Accelerometer

Python libraries used in this project include:
`pandas`
`numpy`
`matplotlib.pyplot`
`scipy`
`statsmodels`

NOTE: Program will run for at most 1 minute, depending on different computers and it's hardware. Please be patient :)

## How to run the program in Linux workspace

`python3 walking_speed_estimation.py Hand_Data/Sam_Hand1.txt`

`python3 walking_speed_estimation.py Pocket_Data/Lillian_Pocket2.txt`

`python3 walking_speed_estimation.py Foot_Data/Lexi_Foot3.txt`

The above are examples of running the program with different input files. All input files will be saved in these folders:

`Hand_Data`
`Pocket_Data`
`Foot_Data`

Each folder contains input files with the format: Name_Position#.txt

For example: Sam_Hand1.txt or Lillian_Pocket2.txt or Lexi_Foot3.txt and so on.

Hand_Data and Pocket_Data each contain 3 input files for 3 different members, labelled from 1 to 3, totalling to 9 files.

Foot_Data cotains 5 input files for 3 different members, labelled from 1 to 5, totalling to 15 files.

There will be one `Velocity_Graph.png` output everytime the program ran, showing the graph of the resulted walking speed. The calculated average velocity will also be printed in the terminal window.
