# LPVU-Net

1. This code is for the paper：
   
   Learning deep priors: variational optimization inspired unfolding network for underwater image enhancement (currently under review in IEEE Transactions on Neural Networks and Learning Systems).

2. Installation

   This code is based on MatConvNet package. We provide a precompiled "matlab" folder. You can download from [Baidu Cloud]( https://pan.baidu.com/s/1FPwMV58hdevJpKhsQ-1zOw?pwd=LPVU ) (Password：LPVU) and [Google Drive](https://drive.google.com/file/d/108ZjaqEIovvfRyVj4zIv0r5kurmxUv92/view?usp=drive_link).
   
   
3. Usage

   Before running the demo, you should first compile the tools:

        cd LPVU-Net/tools

        mexcuda upsample.cu
   
   Next, you can perform the following steps:
   
   (1) Put the test images into the "images" folder.
   
   (2) Run test.m to see the results.
