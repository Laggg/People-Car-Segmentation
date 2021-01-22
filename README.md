# People-Car-Segmentation
This project will show people and car segmentation from poor quality masks using PyTorch.

# Importing resulting model
``` python
import torch
from model.resnet_unet import ResNetUNet
model = torch.load('model/resnet_unet.pth')
```
