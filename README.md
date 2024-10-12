# Influenza-Thailand
## Requirements
The code has been tested on GTX3050 locally with PyTorch 1.12 and Cuda 11.3.

For convenients, we implemented a sample code on github. 

Please include data paths and selected features there:
https://colab.research.google.com/drive/1n5Kgg2gNacDC24Q6pgqzvQc1F9ufVOnM#scrollTo=Jv7xNSFh2F_5


For local testing with an access to gpu, please feel free to install these libraries:

```Shell
conda create --name influenza python=3.7
conda activate influenza
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch
```
