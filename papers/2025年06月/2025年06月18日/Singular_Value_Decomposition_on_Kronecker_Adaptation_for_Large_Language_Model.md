# # 基于Kronecker适配的奇异值分解在大型语言模型中的应用研究

发布时间：2025年06月18日

`LLM理论` `机器学习`

> Singular Value Decomposition on Kronecker Adaptation for Large Language Model

# 摘要

> 大型预训练的Transformer模型在语言和推理任务中表现优异，但完整的微调过程资源消耗巨大。参数高效微调（PEFT）方法通过精简参数来降低这些成本，然而现有方法各有局限：适配器模块增加推理延迟，随机初始化的低秩更新收敛性欠佳，基于Kronecker的分解则受限于固定秩选择。

我们提出了一种创新的PEFT策略——SoKA（SVD on Kronecker Adaptation），该方法巧妙结合了Kronecker积张量分解、SVD驱动的初始化和频谱感知的动态秩选择。通过Kronecker积SVD（KPSVD）过程，我们能够将完整的权重更新分解为主成分，并压缩为紧凑的Kronecker因子。同时，自适应秩选择算法利用能量阈值和拐点准则，有效去除微不足道的成分。

在LLaMA2-7B模型上的实证评估显示，SoKA仅需0.99M可训练参数，比LoRA/PiSSA减少了25%，同时保持或超越了基线性能。此外，SoKA在收敛速度和梯度稳定性方面表现更优，充分展现了其在大规模模型适配中的强大鲁棒性和高效性。

> Large pre-trained Transformer models achieve state-of-the-art results across diverse language and reasoning tasks, but full fine-tuning incurs substantial storage, memory, and computational overhead. Parameter-efficient fine-tuning (PEFT) methods mitigate these costs by learning only a small subset of task-specific parameters, yet existing approaches either introduce inference-time latency (adapter modules), suffer from suboptimal convergence (randomly initialized low-rank updates), or rely on fixed rank choices that may not match task complexity (Kronecker-based decompositions).
  We propose SoKA (SVD on Kronecker Adaptation), a novel PEFT strategy that combines Kronecker-product tensor factorization with SVD-driven initialization and spectrum-aware dynamic rank selection. Our Kronecker-Product SVD (KPSVD) procedure extracts principal components of the full weight update into compact Kronecker factors, while an adaptive rank selection algorithm uses energy-threshold and elbow-point criteria to prune negligible components.
  Empirical evaluation on LLaMA2-7B across arithmetic reasoning (GSM8K), formal mathematics (MATH), and code generation (MBPP) demonstrates that SoKA requires only 0.99M trainable parameters, 25% fewer than LoRA/PiSSA, while matching or exceeding baseline performance. Moreover, SoKA exhibits faster convergence and more stable gradients, highlighting its robustness and efficiency for large-scale model adaptation.

[Arxiv](https://arxiv.org/abs/2506.15251)