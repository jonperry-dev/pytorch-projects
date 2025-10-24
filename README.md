# PyTorch Propjects

This pytorch-projects repo will hold various torch porjects over many different deep learning taks, including vision and reinforcement learning.

# Install

Create a virtual environment:
```bash
python3.10 -m venv .venv
```
After the virtual environment is made, install the primary dependencies with this line:
```bash
pip install -e .[dev]
```
You will need pytorch, which we currently support using cuda 11, cuda 12, or cpu:

```bash
# install cpu
hatch run torch-cpu
# install gpu for cuda 11
hatch run torch-cu11
# install gpu for cuda 12
hatch run torch-cu12
```