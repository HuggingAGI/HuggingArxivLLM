# 用于具有数据和模型并行性的语言模型分布式训练的自适应批量大小调度

发布时间：2024年12月30日

`LLM应用` `语言模型` `分布式训练`

> Adaptive Batch Size Schedules for Distributed Training of Language Models with Data and Model Parallelism

# 摘要

> 在大规模模型的训练中，选择恰当的批量大小极为关键，然而这却存在一个内在且难以避免的难题：大批次训练能在内存利用方面提升训练效率，可泛化性能却常因梯度噪声量少而变差。尽管面临此困境，语言模型训练中选择批量大小的常规操作往往优先考虑训练效率——要么运用具备数据并行性的恒定大尺寸，要么执行批量大小预热方案。但此类批量大小方案的设计仍属启发式，且往往难以适应训练动态，从而形成设计自适应批量大小方案的挑战。鉴于丰富的可用数据集以及语言模型对数据的渴求特性，数据并行性已成为不可或缺的分布式训练范式，能够采用更大的批量大小进行梯度计算。然而，普通的数据并行性要求每个工作节点都有模型参数、梯度和优化器状态的副本，这限制了数十亿参数的大型模型的训练。为优化内存使用，必须采用更高级的并行策略。在本研究中，我们提出了与数据并行性和模型并行性兼容的通用且有理论原则的自适应批量大小方案。我们利用 PyTorch Fully Sharded Data Parallel 开发了实用的实现，助力不同规模语言模型的预训练。我们通过实验表明，在 Llama 家族模型的预训练中，我们所提出的方法优于恒定批量大小和启发式批量大小预热方案，尤其在多达 30 亿参数的较小模型上表现出色。我们还为采用 Adam 的一般平滑非凸目标的此类自适应批量大小方案建立了理论收敛保证。

> An appropriate choice of batch sizes in large-scale model training is crucial, yet it involves an intrinsic yet inevitable dilemma: large-batch training improves training efficiency in terms of memory utilization, while generalization performance often deteriorates due to small amounts of gradient noise. Despite this dilemma, the common practice of choosing batch sizes in language model training often prioritizes training efficiency -- employing either constant large sizes with data parallelism or implementing batch size warmup schedules. However, such batch size schedule designs remain heuristic and often fail to adapt to training dynamics, presenting the challenge of designing adaptive batch size schedules. Given the abundance of available datasets and the data-hungry nature of language models, data parallelism has become an indispensable distributed training paradigm, enabling the use of larger batch sizes for gradient computation. However, vanilla data parallelism requires replicas of model parameters, gradients, and optimizer states at each worker, which prohibits training larger models with billions of parameters. To optimize memory usage, more advanced parallelism strategies must be employed. In this work, we propose general-purpose and theoretically principled adaptive batch size schedules compatible with data parallelism and model parallelism. We develop a practical implementation with PyTorch Fully Sharded Data Parallel, facilitating the pretraining of language models of different sizes. We empirically demonstrate that our proposed approaches outperform constant batch sizes and heuristic batch size warmup schedules in the pretraining of models in the Llama family, with particular focus on smaller models with up to 3 billion parameters. We also establish theoretical convergence guarantees for such adaptive batch size schedules with Adam for general smooth nonconvex objectives.

[Arxiv](https://arxiv.org/abs/2412.21124)