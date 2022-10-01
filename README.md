# balloon-diffusion
A Stable Diffusion model trained only on inflation content.

# Model
Link to **PRUNED** Balloon Diffusion v1.1 Model:
https://drive.google.com/file/d/1EN7zQkv4z4m7et5IuLOm-DIO9l-ILWFN/view?usp=sharing

# How to Use
I will not provide instructions here, but check out the stable-diffusion-webui repo to use it.
https://github.com/sd-webui/stable-diffusion-webui
Note: **An NVIDIA GPU is required, preferably above 6gb of VRAM!!**

# About Balloon Diffusion
Balloon Diffusion is a project of mine a few weeks in the making, with 1.0 being trained on 22,078 samples of inflation art.
1.1 is much more ambitious, being trained on 73,492 samples of inflation content.
1.2 is coming soon, however I currently lack the resources to train a model of this size, with my current 1.2 dataset sitting at over 150k samples at the time of writing.

This project is based on haru's Waifu Diffusion, and he was immensely helpful on this project.
HOWEVER, due to the VRAM requirements of Waifu Diffusion (needing 30gb of VRAM or more to train) I can only feasibly train this on cloud GPUS, and I trained 1.0 and 1.1 on A6000s through vast.ai.

# What does "pruned" mean?
"Pruning" a model is removing training checkpoints from said model. It works the same when you use it to create images, however, you cannot use a pruned model to train from that point. The pruned version of Balloon Diffusion 1.1 sits at 3.58 GB, the unpruned version sits at over **14 GB** hence why it isn't included here.

# Support
If you would like to help with the training of Balloon Diffusion 1.2, I have a Ko-fi, and a goal set for the (approximate, these are my calculations) amount needed to train Balloon Diffusion 1.2. It will get trained eventually, however it is a while off at the moment.

# Comparisions and Samples:
Coming Soon
