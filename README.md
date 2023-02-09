# ResNet-Implementation

## Creating Notebook
**Name:** resnet-implementation-<your_name>

**Image:** tensorflow:deepops-kubeflow-minimal

**CPU/RAM:**
- CPU: 8
- Memory: 16.0Gi

**GPUs:**
- Number of GPUs: 1
- GPU Vendor: NVIDIA-MIG-20GB

**Workspace Volume:**
- [x] Don't use Persistent Storage for User's home

*Leave rest as it is and `LAUNCH` notebook*

`CONNECT` Notebook Server

## Change Directory
```bash
cd /workspace/
```

## Clone GitHub Repository
```bash
git clone https://github.com/hamzaziizzz/ResNet-Implementation.git
```

## Change Directory
```bash
cd ResNet-Implementation/
```

## Install Ubuntu-based Libraries
```bash
apt update
```
```bash
apt install ffmpeg libsm6 libxext6 -y
```

## Install Python Dependencies
```bash
pip install -r requirements.txt
```

*Run Jupyter Notebook*
