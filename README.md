# Deep-Learning-GPU-Performance-Profiling

By profiling CNN and Transformer workloads, we show that CNN inference is dominated by compute kernels (cuDNN convolution), whereas Transformer attention increasingly stresses memory bandwidth as sequence length grows. Batch size controls GPU utilization and mixed precision primarily benefits compute-bound workloads.
