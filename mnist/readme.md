# Handwriting Recognition with PyTorch & MNIST Dataset

* Path  ``` $ .. sand/active/convolutional-neural-networks ```
* Master Repo : [Convoluted Neural Networks](https://github.com/mori-c/convolutional-neural-networks)
* Project : [Curriculum](https://github.com/mori-c/convolutional-neural-networks/projects/1)
* Tutorial : [Torch.nn](https://pytorch.org/tutorials/beginner/nn_tutorial.html)
* PyTorch Repo  :  [Neural Net Tutorial](https://is.gd/KXdGOU)

### Install Prerequisites

* PyTorch
* Python 3.0+
* Anaconda or pip
* numpy
* torch
* torchvision

**Verification**

```
from __future__ import print_function
import torch
x = torch.rand(5, 3)
print(x)
```

Similar output target:
```
tensor([[0.0135, 0.2768, 0.8822],
        [0.2277, 0.3493, 0.1918],
        [0.2136, 0.9960, 0.6158],
        [0.1255, 0.8844, 0.8253],
        [0.1816, 0.7173, 0.1842]])
```

Check if GPU driver & CUDA is enabled
*MacOS Binaries dont support CUDA, install from source if CUDA is needed*

```
import torch
torch.cuda.is_available()
```

More info, found on [PyTorch: Get Started](https://pytorch.org/get-started/locally/)

