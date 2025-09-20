# RDS4Everyone
## development enviroment
This program is developed under the Jupyter Lab enviroments.
Python3 and required import modules are below.

import cv2
import glob
import matplotlib.image as mpimg
import matplotlib.pyplot as plt
import math 
import numpy as np
import os

## How it works
prepere image file of single image random dot stereogram (RDS) aka autogram or Magic Eye. jpg, png etc. opencv aceptable image format is ok.

images/RDS/ directory has 3 sample single image RDS files.

<img width="600" height="600" alt="16_100_ROBO" src="https://github.com/user-attachments/assets/8cd5999e-6161-48c1-9a74-08683338fbb3" />

find main routine part in RDS to Anaglyph 3D - RDS parallax estimation cell, and set 
rds_file valiable like below.

rds_file = 'your_rds_file.jpg' 

and just run from top cell to next.
sliding window process needs a little bit time to scan horizontal. after that, the result will show in  Outputs.

<img width="636" height="656" alt="download" src="https://github.com/user-attachments/assets/bfca1e5b-b1cc-41b6-b286-ce929c07e171" />
<img width="636" height="656" alt="download" src="https://github.com/user-attachments/assets/98d994a5-c18c-4bb9-ace7-aa12f2b7e85f" />
<img width="636" height="656" alt="download" src="https://github.com/user-attachments/assets/bf339428-47f1-496d-bf44-6fd3b66b23a0" />
<img width="636" height="656" alt="download" src="https://github.com/user-attachments/assets/db993b5d-6dd1-4af8-85d7-05de3e671fdb" />

## References
I posted paper for related work on Academia.edu. if you are interested, please visit.
https://www.academia.edu/129165302/Parallax_Estimation_in_Stereo_Vision_without_Cue

Thanks,
