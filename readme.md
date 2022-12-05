## Install


```bash
git clone --recurse-submodules https://github.com/4N3MONE/community-chatbot.git
cd community-chatbot
pip3 install -r requirements.txt 
```

## How to Train

```bash
CUDA_VISIBLE_DEVICES=0 python train_torch.py --gpus 1 --train --max_epochs 2 --version fmkorea
```

## How to Chat!

```bash
# CUDA_VISIBLE_DEVICES=0 python train.py --chat
CUDA_VISIBLE_DEVICES=0 python train_torch.py --gpus 1 --chat
