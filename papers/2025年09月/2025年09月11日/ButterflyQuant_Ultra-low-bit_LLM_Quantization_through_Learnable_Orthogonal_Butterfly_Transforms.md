# ButterflyQuant：基于可学习正交蝴蝶变换的超低比特大型语言模型量化

发布时间：2025年09月11日

`LLM理论` `基础理论`

> ButterflyQuant: Ultra-low-bit LLM Quantization through Learnable Orthogonal Butterfly Transforms

# 摘要

> 大型语言模型内存占用巨大，严重限制了其在消费级硬件上的部署。量化技术通过降低数值精度减少内存，但极端的2位量化会因激活值中的异常值导致性能骤降。QuIP、QuaRot等旋转量化方法通过正交变换在量化前消除异常值，其核心是利用计算不变性：【数学公式】（Q为正交矩阵）。但这些方法采用固定变换（如Hadamard矩阵，可实现最坏情况下的最优相干性【数学公式】），无法适配具体的权重分布。我们观察到不同Transformer层的异常值模式差异显著，因此提出层自适应旋转策略，摒弃“一刀切”的固定变换。为此，我们提出ButterflyQuant，用可学习的蝴蝶变换（通过连续Givens旋转角参数化）替代Hadamard旋转。Hadamard矩阵的离散【数学公式】条目不可微，无法进行梯度学习；而蝴蝶变换的连续参数化不仅支持平滑优化，还能通过构造天然保证正交性。这种正交约束既保证了异常值抑制的理论效果，又将计算复杂度控制在【数学公式】，可学习参数也仅需【数学公式】个。我们还在变换后的激活值上引入均匀性正则化，以生成更平滑的分布，从而更易于量化。模型学习仅需128个校准样本，单GPU上几分钟即可收敛，一次性成本几乎可以忽略。在2位量化的LLaMA-2-7B模型上，ButterflyQuant的困惑度达到15.4，远超QuaRot的22.1。

> Large language models require massive memory footprints, severely limiting deployment on consumer hardware. Quantization reduces memory through lower numerical precision, but extreme 2-bit quantization suffers from catastrophic performance loss due to outliers in activations. Rotation-based methods such as QuIP and QuaRot apply orthogonal transforms to eliminate outliers before quantization, using computational invariance: $\mathbf{y} = \mathbf{Wx} = (\mathbf{WQ}^T)(\mathbf{Qx})$ for orthogonal $\mathbf{Q}$. However, these methods use fixed transforms--Hadamard matrices achieving optimal worst-case coherence $μ= 1/\sqrt{n}$--that cannot adapt to specific weight distributions. We identify that different transformer layers exhibit distinct outlier patterns, motivating layer-adaptive rotations rather than one-size-fits-all approaches. We propose ButterflyQuant, which replaces Hadamard rotations with learnable butterfly transforms parameterized by continuous Givens rotation angles. Unlike Hadamard's discrete $\{+1, -1\}$ entries that are non-differentiable and prohibit gradient-based learning, butterfly transforms' continuous parameterization enables smooth optimization while guaranteeing orthogonality by construction. This orthogonal constraint ensures theoretical guarantees in outlier suppression while achieving $O(n \log n)$ computational complexity with only $\frac{n \log n}{2}$ learnable parameters. We further introduce a uniformity regularization on post-transformation activations to promote smoother distributions amenable to quantization. Learning requires only 128 calibration samples and converges in minutes on a single GPU--a negligible one-time cost. On LLaMA-2-7B with 2-bit quantization, ButterflyQuant achieves 15.4 perplexity versus 22.1 for QuaRot.

[Arxiv](https://arxiv.org/abs/2509.09679)