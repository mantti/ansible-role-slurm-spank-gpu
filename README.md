# ansible-role-slurm-spank-gpu

Ansible role to install [slurm-spank-plugin](https://github.com/stanford-rc/slurm-spank-gpu_cmode) to allow user to control 
GPU:s compute_mode. Depends on [slurm-spank-lua](https://github.com/stanford-rc/slurm-spank-lua).

I had to modify its SPEC-file as fgci-clusters use slurm-ohpc and slurmd-devel-ohpc packages instead
of EPEL's correspendences named as slurm and slurm-devel.

