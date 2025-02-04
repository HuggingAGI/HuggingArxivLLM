# SubTrack your Grad: 梯度子空间跟踪——实现内存和时间高效的全参数 LLM 训练

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要讨论的是如何优化大型语言模型（LLMs）的训练过程，提出了一种新的优化方法SubTrack-Grad，旨在减少训练时间和内存使用，同时保持或提升模型性能。这涉及到LLM的训练理论和优化技术，属于LLM理论范畴。` `机器学习` `优化算法`

> SubTrack your Grad: Gradient Subspace Tracking for Memory and Time Efficient Full-Parameter LLM Training

# 摘要

> # 摘要
训练大型语言模型（LLMs）因其庞大的模型规模和复杂的优化器状态，耗费大量时间和计算资源。为应对这一挑战，近期方法如BAdam通过部分权重更新提升时间和内存效率，但有时会牺牲性能。而GaLore则通过全参数训练优化内存使用，保持性能，但可能增加时间复杂度。我们提出SubTrack-Grad，一种基于子空间跟踪的优化方法，利用梯度的低秩结构和Grassmannian几何，结合估计误差和先前识别的子空间，高效跟踪演变的梯度子空间。与GaLore相比，SubTrack-Grad在性能上表现更优或相当，同时显著优于BAdam，尽管BAdam在时间效率上表现优异，但性能有所妥协。SubTrack-Grad在GLUE任务上减少高达20.57%的墙时间（平均减少15%），在SuperGLUE任务上减少高达65%的墙时间（平均减少22%）。值得注意的是，对于3B参数的模型，GaLore相比全秩训练增加了157%的墙时间，而SubTrack-Grad仅增加31%，减少49%的墙时间，同时享受与GaLore相同的内存优化。

> Training Large Language Models (LLMs) demand significant time and computational resources due to their large model sizes and optimizer states. To overcome these challenges, recent methods, such as BAdam, employ partial weight updates to enhance time and memory efficiency, though sometimes at the cost of performance. Others, like GaLore, focus on maintaining performance while optimizing memory usage through full parameter training, but may incur higher time complexity. By leveraging the low-rank structure of the gradient and the Grassmannian geometry, we propose SubTrack-Grad, a subspace tracking-based optimization method that efficiently tracks the evolving gradient subspace by incorporating estimation errors and previously identified subspaces. SubTrack-Grad delivers better or on-par results compared to GaLore, while significantly outperforming BAdam, which, despite being time-efficient, compromises performance. SubTrack-Grad reduces wall-time by up to 20.57% on GLUE tasks (15% average reduction) and up to 65% on SuperGLUE tasks (22% average reduction) compared to GaLore. Notably, for a 3B parameter model, GaLore incurred a substantial 157% increase in wall-time compared to full-rank training, whereas SubTrack-Grad exhibited a 31% increase, representing a 49% reduction in wall-time, while enjoying the same memory reductions as GaLore.

[Arxiv](https://arxiv.org/abs/2502.01586)