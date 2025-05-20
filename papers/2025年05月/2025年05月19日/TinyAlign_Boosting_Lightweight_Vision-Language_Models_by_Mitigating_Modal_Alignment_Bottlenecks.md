# # 摘要  
TinyAlign：突破模态对齐瓶颈，助力轻量级视觉语言模型性能提升。

发布时间：2025年05月19日

`其他` `计算机视觉` `多模态`

> TinyAlign: Boosting Lightweight Vision-Language Models by Mitigating Modal Alignment Bottlenecks

# 摘要

> 轻量级视觉语言模型（VLMs）在资源受限的应用场景中发挥着不可或缺的作用。当前主流的视觉与语言模型对齐方法是冻结视觉编码器和语言模型，仅训练小型连接模块。然而，这种方法对语言模型的内在能力高度依赖，对于表示能力有限的轻量级模型而言，这可能并非最优选择。本研究通过互信息的视角，揭示了这一对齐瓶颈的本质：语言模型的受限容量本质上限制了多模态输入与输出之间有效互信息（EMI）的流动，从而影响了对齐质量。为解决这一挑战，我们提出了 TinyAlign，一个受检索增强生成启发的全新框架。该框架通过从记忆库中检索相关上下文来丰富多模态输入，从而提升对齐效果。大量实证评估表明，TinyAlign显著降低了训练损失，加速了收敛速度，并提升了任务性能。尤为值得一提的是，该方法使模型仅需40%的微调数据即可达到基线性能水平，展现了卓越的数据效率。我们的工作不仅为开发更强大的轻量级 VLMs 提供了一条实用路径，还引入了一个全新的理论视角，有助于更好地理解并解决受限多模态系统中的对齐瓶颈问题。

> Lightweight Vision-Language Models (VLMs) are indispensable for resource-constrained applications. The prevailing approach to aligning vision and language models involves freezing both the vision encoder and the language model while training small connector modules. However, this strategy heavily depends on the intrinsic capabilities of the language model, which can be suboptimal for lightweight models with limited representational capacity. In this work, we investigate this alignment bottleneck through the lens of mutual information, demonstrating that the constrained capacity of the language model inherently limits the Effective Mutual Information (EMI) between multimodal inputs and outputs, thereby compromising alignment quality. To address this challenge, we propose TinyAlign, a novel framework inspired by Retrieval-Augmented Generation, which strategically retrieves relevant context from a memory bank to enrich multimodal inputs and enhance their alignment. Extensive empirical evaluations reveal that TinyAlign significantly reduces training loss, accelerates convergence, and enhances task performance. Remarkably, it allows models to achieve baseline-level performance with only 40\% of the fine-tuning data, highlighting exceptional data efficiency. Our work thus offers a practical pathway for developing more capable lightweight VLMs while introducing a fresh theoretical lens to better understand and address alignment bottlenecks in constrained multimodal systems.

[Arxiv](https://arxiv.org/abs/2505.12884)