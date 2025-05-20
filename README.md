# MCDR
A Multilevel Cross-Domain Relational Network for Drug Repositioning

## Baselines

DRHGCN:[TheWall9/DRHGCN](https://github.com/TheWall9/DRHGCN)

DRWBNCF:[GitHub - luckymengmeng/DRWBNCF](https://github.com/luckymengmeng/DRWBNCF)

DRGBCN:[huangyueshiqi/DRGBCN: paper-DRGBCN](https://github.com/huangyueshiqi/DRGBCN)

DRGCL:[GitHub - Jiaxiao123/DRGCL](https://github.com/Jiaxiao123/DRGCL)

AutoDR:[1yiw/AutoDR: This is the PyTorch implementation for AutoDR proposed in the paper Automatic collaborative learning for drug repositioning.](https://github.com/1yiw/AutoDR)

## Dependencies

- python == 3.7
- pytorch == 1.9.0
- rdkit == 2020.9.5.2
- dgl = 0.6.1
- scikit-learn == 1.0.2

### Usage

train MCDR in 10-fold cross-validation :

python train.py

train MCDR in cold start:

python train_cold.py