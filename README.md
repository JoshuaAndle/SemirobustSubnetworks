# SemirobustSubnetworks
Code for transfer of robustness from semirobust subnetwork
We provide here the directories for scripts used in running Algorithm 1 (./MI) and Algorithm S1 (./Linear). 

We additionally provide .ipynb files in each directory to run the corresponding experiments, but due to size limitations have omitted the datasets and network weights. 

Prior to running each algorithm, the networks need to be pretrained with the Pretraining.py script in ./MI. This can be done through the .ipynb in the same directory

Code in ./MI is set up to work with CIFAR-10 and CIFAR-100 for datasets, ResNet-18 and WideResNet-34-10 for networks, and 'none', 'fgsm', 'pgd', or 'autoattack' for the attacks

Code for generating figures isn't included
