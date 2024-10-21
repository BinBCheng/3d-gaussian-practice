# 3d-gaussian-practice

用于记录学习3d gaussian的过程

恒源云配置3D Gaussian的过程：

首先选择显卡，创建环境：
4090,cuda 11.8,python 3.8.10,torch 2.0.0,torchvision 0.15.1,torchaudio 2.0.1

然后下载代码：
git clone https://github.com/graphdeco-inria/gaussian-splatting --recursive

然后配置C++环境：
sudo apt-get update
sudo apt install build-essential
sudo apt-get install ninja-build

然后配置高斯子模块：
#gaussian submodules
pip install submodules/diff-gaussian-rasterization
pip install submodules/simple-knn

然后配置一些必要的库：
pip install plyfile tensorboard tqdm

