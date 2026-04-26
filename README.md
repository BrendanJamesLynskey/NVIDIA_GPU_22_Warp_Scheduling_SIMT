# Warp Scheduling & SIMT — How the SM Actually Issues Instructions

The microarchitecture of warp issue: SM partitions, warp schedulers, instruction latencies, occupancy versus ILP, divergence and reconvergence, predication versus branching, independent thread scheduling (Volta+), and the common stall patterns that decide whether your kernel runs at peak. Includes an interactive issue-rate predictor that turns block size and register pressure into predicted IPC and bottleneck.

**Live site:** https://brendanjameslynskey.github.io/NVIDIA_GPU_22_Warp_Scheduling_SIMT/

Part of the [NVIDIA GPU Architectures series](https://github.com/BrendanJamesLynskey/LLMs#nvidia-gpu-architectures).
