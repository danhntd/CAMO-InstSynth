# CAMO-InstSynth

This repository is the official implementation of the paper entitled: **CAMO-InstSynth: Few-shot Camouflage Instance Segmentation with Multi-Conditional Background Synthesis and Generative Augmentation**, accepted to the 18th Asian Conference
on Intelligent Information and Database Systems (ACIIDS), 2026. <br>
**Authors:** Thanh-Danh Nguyen, Vinh-Tiep Nguyen†, Kunpeng Li, and Tam V. Nguyen.

[[Paper]](https://doi.org/) [[Code]](https://github.com/danhntd/CAMO-InstSynth) [[Project Page]](https://danhntd.github.io/projects.html#CAMO-InstSynth)

## Updates:
- [Feb 7, 2026] The manuscript is accepted to **the 18th Asian Conference
on Intelligent Information and Database Systems (ACIIDS), 2026**. :zap::zap:
- [Feb 12, 2025] The GitHub repository is initialized. Please stay tuned for further updates!


## 1. Environment Setup
Download and install Anaconda with the recommended version from [Anaconda Homepage](https://www.anaconda.com/download): [Anaconda3-2019.03-Linux-x86_64.sh](https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh) 
 
```
git clone https://github.com/danhntd/CAMO-InstSynth.git
cd CAMO-InstSynth
curl -O https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
bash Anaconda3-2019.03-Linux-x86_64.sh
```

After completing the installation, please create and initiate the workspace with the specific versions below. The experiments were conducted on a Linux server with a single `GeForce RTX 2080Ti GPU`, CUDA 10.2, Torch 1.7.

```
conda create --name CAMO-InstSynth python=3
conda activate CAMO-InstSynth
conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cudatoolkit=10.2 -c pytorch
conda env update -f enviroment.yml --prune
```


## 2. Data Preparation



## 3. Training Pipeline


## 4. Results and Visualization


## Citation
Please use this bibtex to cite this repository:
```
@article{
}
```


<!-- ## Acknowledgements -->
