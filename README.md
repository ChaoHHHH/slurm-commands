# slurm-commands
```
srun -p 4090 --gres=gpu:1 python mace_run.py
#申请一个 4090 节点的一块gpu，执行 python mace_run.py，结果直接输出到当前终端

ssh g14 "nvidia-smi"
#查看目标节点的GPU情况

srun -p 4090 --cpus-per-task=16 python mace_run.py
#申请16个核，不使用gpu

scancel -u your_name
#停止你的全部作业
```
