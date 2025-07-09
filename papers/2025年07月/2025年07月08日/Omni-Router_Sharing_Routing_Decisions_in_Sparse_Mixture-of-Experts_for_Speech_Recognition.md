# # Omni-Router：稀疏专家混合模型中的路由决策共享机制（用于语音识别）

发布时间：2025年07月08日

`LLM理论` `语音识别` `语音处理`

> Omni-Router: Sharing Routing Decisions in Sparse Mixture-of-Experts for Speech Recognition

# 摘要

> 混合专家（MoE）架构已从语言建模扩展到自动语音识别（ASR）。传统的MoE方法，如Switch Transformer，在每一层独立路由专家。我们的分析表明，大多数层中的路由器选择专家的方式与其他层的路由器选择之间关联性不强。为了增加不同层之间专家的合作，并鼓励更大的专业化，我们在不同的MoE层之间使用共享的路由器。我们称这种模型为\emph{Omni-router Transformer}。在大规模伪标签数据集上的广泛实验以及在10个多样化的、跨域的ASR基准上的评估表明，Omni-router Transformer能够实现更低的训练损失，并且始终优于密集和Switch Transformer模型，分别将平均单词错误率降低了11.2%和8.2%，同时提供结构化的专家使用和对多样化数据的增强鲁棒性。

> Mixture-of-experts (MoE) architectures have expanded from language modeling to automatic speech recognition (ASR). Traditional MoE methods, such as the Switch Transformer, route experts independently within each layer. Our analysis reveals that routers in most layers make expert choices that are not strongly correlated with the choices of the routers in other layers. To increase the cooperation between experts in different layers and encourage greater specialization, we use a shared router across different MoE layers. We call this model \emph{Omni-router Transformer}. Extensive experiments on a large-scale pseudo-labeled dataset and evaluations across 10 diverse, out-of-domain ASR benchmarks demonstrate that the Omni-router Transformer is able to achieve lower training loss and consistently outperform dense and Switch Transformer models, reducing average word error rates by 11.2% and 8.2%, respectively, while providing structured expert usage and improved robustness to diverse data.

[Arxiv](https://arxiv.org/abs/2507.05724)