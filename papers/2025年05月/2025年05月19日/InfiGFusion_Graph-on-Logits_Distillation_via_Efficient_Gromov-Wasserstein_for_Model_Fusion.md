# InfiGFusion: 通过高效 Gromov-Wasserstein 实现图对数蒸馏的模型融合方法

发布时间：2025年05月19日

`LLM应用` `人工智能` `机器学习`

> InfiGFusion: Graph-on-Logits Distillation via Efficient Gromov-Wasserstein for Model Fusion

# 摘要

> 大型语言模型（LLMs）的突破推动了将异构开源模型融合到统一系统中的研究，以充分利用它们的互补优势。现有的基于logit的融合方法虽保持了推理效率，但忽视了跨维度交互所编码的语义依赖关系，这些关系反映了模型内部推理过程中不同token类型之间的相互作用，对适应多样化生成行为至关重要。为此，我们提出了	extbf{InfiGFusion}，这是首个结构感知的融合框架，采用了新颖的	extit{基于Logit的图蒸馏}（GLD）损失函数。具体而言，我们通过保留每个输出的前$k$个logit，并在序列位置上聚合它们的外积，形成一个全局共激活图，其中节点代表词汇通道，边量化它们的联合激活程度。为了确保可扩展性和效率，我们设计了一种基于排序的闭式近似方法，将格罗莫夫-瓦瑟斯坦距离的原始$O(n^4)$成本降低到$O(n \log n)$，并提供了可证明的近似保证。实验结果表明，GLD显著提升了融合质量和稳定性。InfiGFusion在涵盖推理、编码和数学的11个基准测试中超越了现有最优模型和融合基线。尤其在复杂推理任务中表现突出，与SFT相比，在多步算术任务上提升了+35.6，在因果判断任务上提升了+37.06，展示了其在多步和关系推理方面的卓越能力。

> Recent advances in large language models (LLMs) have intensified efforts to fuse heterogeneous open-source models into a unified system that inherits their complementary strengths. Existing logit-based fusion methods maintain inference efficiency but treat vocabulary dimensions independently, overlooking semantic dependencies encoded by cross-dimension interactions. These dependencies reflect how token types interact under a model's internal reasoning and are essential for aligning models with diverse generation behaviors. To explicitly model these dependencies, we propose \textbf{InfiGFusion}, the first structure-aware fusion framework with a novel \textit{Graph-on-Logits Distillation} (GLD) loss. Specifically, we retain the top-$k$ logits per output and aggregate their outer products across sequence positions to form a global co-activation graph, where nodes represent vocabulary channels and edges quantify their joint activations. To ensure scalability and efficiency, we design a sorting-based closed-form approximation that reduces the original $O(n^4)$ cost of Gromov-Wasserstein distance to $O(n \log n)$, with provable approximation guarantees. Experiments across multiple fusion settings show that GLD consistently improves fusion quality and stability. InfiGFusion outperforms SOTA models and fusion baselines across 11 benchmarks spanning reasoning, coding, and mathematics. It shows particular strength in complex reasoning tasks, with +35.6 improvement on Multistep Arithmetic and +37.06 on Causal Judgement over SFT, demonstrating superior multi-step and relational inference.

[Arxiv](https://arxiv.org/abs/2505.13893)