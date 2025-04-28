# RobustCLIP
CSE 8803-IUQ Project
Ajeet Subramanian, Michael Zhou, Mehrdad Moradi

The working code for the projects are in the jupyter notebooks CLIP-CIFAR10.ipynb and CLIP-CIFAR10-MC.ipynb. CLIP-CIFAR10-MC.ipynb has the code with MC dropout and CLIP-CIFAR10.ipynb is the base CLIP model. Running each cell sequentially should lead to working code, where training takes roughly 2-3 minutes per epoch if on a GPU. 

## Dataset Download Instructions
To use the CIFAR-10 dataset, refer to this website: https://www.cs.toronto.edu/~kriz/cifar.html

## Installations Needed
Pytorch and Torchvision
- Installation Command: conda install pytorch torchvision pytorch-cuda=12.1 -c pytorch -c nvidia
CLIP
- Installation Command: pip install git+https://github.com/openai/CLIP.git


