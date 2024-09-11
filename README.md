# 🚀 Olive tutorial

This repo provides a tutorial on how to get started with Olive finetuning. You'll need the following:

- An Nvidia GPU device
- A Python installation

## Run on Colab

You can run the [Olive tutorial for free on Google Colab](https://colab.research.google.com/github/samuel100/olive-tutorial/blob/main/notebooks/olive-finetuning-tinyllama.ipynb).

## Running locally or Cloud VM

The tutorial is available in [this Jupyter notebook](notebooks/olive-finetuning-tinyllama-local.ipynb). We recommend creating a new Python environment to run the notebook in:

```bash
git clone https://github.com/samuel100/olive-tutorial.git
cd olive-tutorial
conda create -n -y olive-ai python=3.11
conda activate olive-ai
pip install -r requirements.txt
sudo apt-get -y install cudnn9-cuda-12
```
