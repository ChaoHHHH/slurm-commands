# slurm-commands
```
srun -p 4090 --gres=gpu:1 python mace_run.py
#申请一个 4090 节点的一块gpu，执行 python mace_run.py，结果直接输出到当前终端
```
