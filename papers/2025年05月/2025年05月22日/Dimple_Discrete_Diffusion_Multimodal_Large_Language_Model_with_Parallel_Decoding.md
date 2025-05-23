# Dimple: 离散扩散多模态大型语言模型，支持并行解码

发布时间：2025年05月22日

`LLM理论` `多模态模型`

> Dimple: Discrete Diffusion Multimodal Large Language Model with Parallel Decoding

# 摘要

> 在本研究中，我们提出了首个离散扩散多模态大型语言模型（DMLLM）——Dimple。通过研究，我们发现单纯采用离散扩散方法训练会导致显著的训练不稳定性、次优性能以及严重的长度偏差问题。为了解决这些挑战，我们创新性地设计了一种结合初始自回归阶段与后续扩散阶段的训练范式。基于此，我们开发了Dimple-7B模型，该模型在与LLaVA-NEXT相同的训练数据集和训练管道下进行训练，最终在性能上超越了LLaVA-NEXT 3.9%，充分证明了DMLLM能够达到与自回归模型相当的性能水平。为了进一步提升推理效率，我们提出了一种名为“自信解码”的解码策略，该策略通过动态调整每一步生成的令牌数量，显著减少了生成迭代次数。在自回归模型中，生成过程的正向迭代次数等于响应长度，而通过自信解码，Dimple所需的迭代次数仅为【数学公式】。此外，我们重新实现了自回归模型中的预填充技术，并证明该技术在大多数基准评估中对性能影响微乎其微，同时带来了1.5倍至7倍的速度提升。我们还深入探索了Dimple利用结构先验精确控制其响应的能力。这些先验不仅使得生成结构化响应的方式与传统的基于指令或思维链提示方法不同，还允许对响应格式和长度进行精细控制，而这在自回归模型中往往难以实现。总体而言，这项研究不仅验证了DMLLM的可行性和优势，还显著提升了其推理效率和可控性。代码和模型已在GitHub上开源，地址为https://github.com/yu-rp/Dimple，欢迎访问和使用。

> In this work, we propose Dimple, the first Discrete Diffusion Multimodal Large Language Model (DMLLM). We observe that training with a purely discrete diffusion approach leads to significant training instability, suboptimal performance, and severe length bias issues. To address these challenges, we design a novel training paradigm that combines an initial autoregressive phase with a subsequent diffusion phase. This approach yields the Dimple-7B model, trained on the same dataset and using a similar training pipeline as LLaVA-NEXT. Dimple-7B ultimately surpasses LLaVA-NEXT in performance by 3.9%, demonstrating that DMLLM can achieve performance comparable to that of autoregressive models. To improve inference efficiency, we propose a decoding strategy termed confident decoding, which dynamically adjusts the number of tokens generated at each step, significantly reducing the number of generation iterations. In autoregressive models, the number of forward iterations during generation equals the response length. With confident decoding, however, the number of iterations needed by Dimple is even only $\frac{\text{response length}}{3}$. We also re-implement the prefilling technique in autoregressive models and demonstrate that it does not significantly impact performance on most benchmark evaluations, while offering a speedup of 1.5x to 7x. Additionally, we explore Dimple's capability to precisely control its response using structure priors. These priors enable structured responses in a manner distinct from instruction-based or chain-of-thought prompting, and allow fine-grained control over response format and length, which is difficult to achieve in autoregressive models. Overall, this work validates the feasibility and advantages of DMLLM and enhances its inference efficiency and controllability. Code and models are available at https://github.com/yu-rp/Dimple.

[Arxiv](https://arxiv.org/abs/2505.16990)