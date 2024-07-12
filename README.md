# helper-functions

# for pytorch

use
from pathlib import Path 
# Download helper functions from Learn PyTorch repo (if not already downloaded)
if Path("torch_help.py").is_file():
  print("torch_help.py already exists, skipping download")
else:
  print("Downloading torch_help.py")
  !wget https://raw.githubusercontent.com/Rhythmbellic/helper-functions/main/torch_help.py

## example usage from torch_help import plot_predictions, plot_decision_boundary
