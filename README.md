# Balloon Diffusion
A Stable Diffusion model trained only on inflation content.

# Model
Link to **PRUNED** Balloon Diffusion v1.1.1 Model:
https://drive.google.com/file/d/17_jY9SjiUFKawPWpfYRcxToQu2ihls3U/view?usp=sharing

# How to Use
Tutorial:
https://docs.google.com/document/d/1qDr8_w6xegwvI21Z7NjuRs_au44YdSJz_CLt-gVrbf8/edit?usp=sharing

Note: **An NVIDIA GPU is required, preferably above 6gb of VRAM!!**

A Jupyter Notebook has been included on this repository, modified to run the Balloon Diffusion v1.1.1 checkpoint using a system like Google Colaboratory. More info on running it is included in the tutorial linked above.

# About Balloon Diffusion
Balloon Diffusion is a project of mine a few weeks in the making, with 1.0 being trained on 22,078 samples of inflation art.
1.1 is much more ambitious, being trained on 73,492 samples of inflation content.
1.2 is coming soon, however I currently lack the resources to train a model of this size, with my current 1.2 dataset sitting at over 150k samples at the time of writing.

This project is based on haru's Waifu Diffusion, and he was immensely helpful on this project.
HOWEVER, due to the VRAM requirements of Waifu Diffusion (needing 30gb of VRAM or more to train) I can only feasibly train this on cloud GPUS, and I trained 1.0 and 1.1 on A6000s through vast.ai.

# What does "pruned" mean?
"Pruning" a model is removing training checkpoints from said model. It works the same when you use it to create images, however, you cannot use a pruned model to train from that point. The pruned version of Balloon Diffusion 1.1 sits at 3.58 GB, the unpruned version sits at over **14 GB** hence why it isn't included here.

# Balloon Diffusion v1.2
is officially a work in progress! I finished up the final dataset a few days ago, with a final total of 188,886 samples of inflation content, with 127,776 unique tags for said content. 

1.2 will be an order of magnitudes better than 1.1.1, not just because of the expanded dataset, I have implemented, with the help of haru, maker of Waifu Diffusion, and the folks over at NovelAI (love you guys!) various improvements to the training code for Balloon Diffusion, including the hotfix included with v1.1.1 to make the default resolution 512x768.

I also have decided to do 10 epochs in total on the data, as opposed to the 4 I did for v1.1. The more epochs I can do, the better. What this means, however, is that it will need significantly more time to train, and more powerful GPUs to run on, in order to complete in a timely manner. I plan to once again rent out A6000s through vast.ai, but a 4x machine, instead of a 2x, which is what v1.1 was trained on.

However, this means that I will need significantly more money to rent out the GPUs to train it on. I recently lost my job, and have put off funding it with my own money for the time being. If you're intereted in supporting, see below, anything is appreciated, nothing is required.

# Support
If you would like to help with the training of Balloon Diffusion 1.2, I have a Ko-fi, and a goal set for the (approximate, these are my calculations) amount needed to train Balloon Diffusion 1.2. It will get trained eventually, however it is a while off at the moment.

https://ko-fi.com/balloonboi

# Updates
If you're interested in seeing progress on Balloon Diffusion, or on the bot I modified to run it, I post about it fairly regularly on my Discord.

https://discord.gg/ECc9T5P43A

If you don't want to join a server, check out my Twitter! While updates are less frequent, I have been posting updates relating to v1.2 for a while.

https://twitter.com/BalloonBoiAD
@BalloonBoiAD
