# # 持续预训练的专家混合模型（MoEs）：你的路由机制究竟有多稳健？

发布时间：2025年03月06日

`LLM理论` `人工智能`

> Continual Pre-training of MoEs: How robust is your router?

# 摘要

> 稀疏激活的专家混合（MoE）变换器是很有前途的基础模型架构。与密集型变换器相比，MoE架构在训练时具有更高的样本效率，并且能够实现更强的性能表现。因此，许多闭源和开源的前沿语言模型已经采用了MoE架构。从业者希望利用大量新数据扩展这些模型的能力，而无需完全重新训练它们。先前研究表明，通过结合经验重放和学习率的重新升温与衰减，可以在密集型仅解码器变换器上实现持续预训练（CPT），性能仅小幅下降。然而，在仅解码器MoE变换器中，路由算法对持续预训练的影响尚不明确：1）MoE路由机制是否会加剧遗忘？2）路由机制能否保持负载平衡？3）密集模型策略是否适用于MoE模型？我们通过一个大规模实证研究（>20亿参数，DeepSeek MoE模型，6000亿token训练），涵盖四种MoE变换器，解答了这些问题。结果表明，即使没有经验重放，Sinkhorn平衡和Z-and-Aux损失平衡路由算法表现出强健性。此外，MoE模型在CPT中保持了样本效率，并且以更低的成本达到重新训练模型的性能。

> Sparsely-activated Mixture of Experts (MoE) transformers are promising architectures for foundation models. Compared to dense transformers that require the same amount of floating point operations (FLOPs) per forward pass, MoEs benefit from improved sample efficiency at training time and achieve much stronger performance. Many closed-source and open-source frontier language models have thus adopted an MoE architecture. Naturally, practitioners will want to extend the capabilities of these models with large amounts of newly collected data without completely re-training them. Prior work has shown that a simple combination of replay and learning rate re-warming and re-decaying can enable the continual pre-training (CPT) of dense decoder-only transformers with minimal performance degradation compared to full re-training. In the case of decoder-only MoE transformers, however, it is unclear how the routing algorithm will impact continual pre-training performance: 1) do the MoE transformer's routers exacerbate forgetting relative to a dense model?; 2) do the routers maintain a balanced load on previous distributions after CPT?; 3) are the same strategies applied to dense models sufficient to continually pre-train MoE LLMs? In what follows, we conduct a large-scale (>2B parameter switch and DeepSeek MoE LLMs trained for 600B tokens) empirical study across four MoE transformers to answer these questions. Our results establish a surprising robustness to distribution shifts for both Sinkhorn-Balanced and Z-and-Aux-loss-balanced routing algorithms, even in MoEs continually pre-trained without replay. Moreover, we show that MoE LLMs maintain their sample efficiency (relative to a FLOP-matched dense model) during CPT and that they can match the performance of a fully re-trained MoE at a fraction of the cost.

[Arxiv](https://arxiv.org/abs/2503.05029)