import sys
sys.version
from pathlib import Path
print(Path.cwd())


import numpy as np
import pandas as pd
import scipy.io as sio
import time
import torch
import torch.nn as nn
from torch.utils.data import DataLoader, TensorDataset, SubsetRandomSampler

import matplotlib.pyplot as plt
import random
import matplotlib as mpl
mpl.rcParams['font.size'] = 14


from torch.cuda import current_device, get_device_name

if torch.cuda.is_available():
    print(f'Current GPU: {get_device_name(current_device())}')
else:
    print('GPU not available.')
