# helper-functions

# for pytorch

### copy paste this code-

from pathlib import Path 

#Download helper functions from Learn PyTorch repo (if not already downloaded)

if Path("torch_help.py").is_file():

  print("torch_help.py already exists, skipping download")
  
else:

  print("Downloading torch_help.py")
  
  !wget https://raw.githubusercontent.com/Rhythmbellic/helper-functions/main/torch_help.py

### example usage 

from torch_help import plot_predictions, plot_decision_boundary

# for Tensorflow

### copy paste this code-

from pathlib import Path 

#Download helper functions from Learn tensorflow repo (if not already downloaded)

if Path("tf_helper.py").is_file():

  print("tf_helper.py already exists, skipping download")
  
else:

  print("Downloading tf_helper.py")
  
  !wget [https://raw.githubusercontent.com/Rhythmbellic/helper-functions/main/torch_help.py](https://github.com/Rhythmbellic/helper-functions/blob/main/tf_helper.py)

### example usage 
from tf_helper import plot_predictions, plot_decision_boundary

