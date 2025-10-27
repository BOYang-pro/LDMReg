# LDMReg

The code of "LDMReg: A Hierarchical Feature-guided Latent Diffusion Model  for Multimodal Image Registration"

For more information, check out the  [[project page](https://cv-reasearch.github.io/LDMReg/)]. 
## Update
- [2025/1] All code will be open after acceptance.
- ....

## Environment

We test the code on PyTorch 1.12.1 + CUDA 11.3.

1. Create a new conda environment
```
conda create -n LDMReg python=3.9
conda activate LDMReg
```

2. Install dependencies
```
pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113

pip install -r requirements.txt
```

