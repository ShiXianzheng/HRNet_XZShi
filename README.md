# HRNet_XZShi

# Distributed training
single node with multi-gpus:
python -m torch.distributed.launch train_Distributed.py --cfg experimental.yaml --multiprocessing-distributed

# Reference 
https://github.com/HRNet/HRNet-Semantic-Segmentation
