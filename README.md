# DNF
A Pytorch implementations of DNF for author's article ["Deep normalization for speaker vectors"](https://arxiv.org/abs/2004.04095)

The neural network structure is based on "Masked Autoregressive Flow", and the source code from [ikostrikov](https://github.com/ikostrikov/pytorch-flows/blob/master/README.md)

## Datasets
```bash
trainingset:Voxceleb 
testset: SITW, CNCeleb
https://
Following this link to download the dataset
```

## Run DNF
```bash
python train.py
```

## Evaluate
```bash
python eval.py
```
