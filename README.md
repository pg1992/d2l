# Installation

If you're using an older compute (e.g. CC 6.1) like I'm doing, then download the correct
package built against CUDA 12.6 (from [PyTorch](https://pytorch.org/get-started/previous-versions/)):

```shell
# CUDA 12.6
pip install torch==2.14.1 torchvision==0.29.1 --index-url https://download.pytorch.org/whl/cu126
```