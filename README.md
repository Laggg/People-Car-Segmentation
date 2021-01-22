# People-Car-Segmentation
This project will show people and car segmentation from poor quality masks using PyTorch.

# Importing resulting model
``` python
import torch
from resnet_unet import ResNetUNet
model = torch.load('resnet_unet.pth')
```
