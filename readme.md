# Socialized Learning: Making Each Other Better Through Multi-Agent Collaboration

The code repository for "Socialized Learning: Making Each Other Better Through Multi-Agent Collaboration"

We provide a demo of the model and the full code will be provided after the paper is accepted.

## Prerequisites
The following packages are required to run the scripts:
- [torch-1.8.1 and torchvision](https://pytorch.org/)
- tqdm

## Dataset
We provide the source code on two benchmark datasets, i.e., CIFAR10 and CIFAR100.

## Code structure
- **checkpoints**: The weights and logs of the experiment.
- **dataset**: Data used in experiment.

## Training scripts
- Train CIFAR100
```
python test_multi_agent_cifar100_ts.py --batch_size 10000 --epochs 1 --num_works_multi_task 0 --num_works_multi_agent 0 --path ./datasets --model_path_s ./checkpoints --model_path_t ./checkpoints --gpu 0
```

## Acknowledgment
We thank the repos providing helpful components/functions in our work.


