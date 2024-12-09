# 用于高效视觉语言推理的交叉自 KV 缓存修剪

发布时间：2024年12月05日

`LLM应用` `多模态` `缓存修剪`

> Cross-Self KV Cache Pruning for Efficient Vision-Language Inference

# 摘要

> KV 缓存修剪已成为降低长上下文自回归生成中内存和计算成本的极具前景的技术。现有的视觉语言模型（VLMs）方法通常依靠大型语言模型（LLMs）的自注意力分数来识别和修剪无关标记。然而，这些方法未考虑到模态间固有的分布差异，常常导致标记重要性估计不准和关键视觉标记的过度修剪。为此，我们提议将注意力分数分解为模态内注意力（同一模态内）和模态间注意力（跨模态），通过分别管理这些不同的注意力类型来实现更精准的 KV 缓存修剪。另外，我们引入了 n-softmax 函数来抵消修剪导致的分布偏移，维持注意力分数原有的平滑度，确保性能稳定。我们最终的免训练方法——	extbf{C}ross-	extbf{S}elf 	extbf{P}runing（CSP），与拥有完整 KV 缓存的模型相比表现出色，且大幅优于以往的修剪方法。在涵盖 29 个多模态数据集的基准 MileBench 上进行的大量评估，证实了 CSP 的有效性，在诸如会话具身对话等挑战性任务中实现了高达 41％的性能提升，同时将 KV 缓存预算降低了 13.6％。代码可在 https://github.com/TerryPei/CSP 获取。

> KV cache pruning has emerged as a promising technique for reducing memory and computation costs in long-context auto-regressive generation. Existing methods for vision-language models (VLMs) typically rely on self-attention scores from large language models (LLMs) to identify and prune irrelevant tokens. However, these approaches overlook the inherent distributional discrepancies between modalities, often leading to inaccurate token importance estimation and the over-pruning of critical visual tokens. To address this, we propose decomposing attention scores into intra-modality attention (within the same modality) and inter-modality attention (across modalities), enabling more precise KV cache pruning by independently managing these distinct attention types. Additionally, we introduce an n-softmax function to counteract distribution shifts caused by pruning, preserving the original smoothness of attention scores and ensuring stable performance. Our final training-free method, \textbf{C}ross-\textbf{S}elf \textbf{P}runing (CSP), achieves competitive performance compared to models with full KV caches while significantly outperforming previous pruning methods. Extensive evaluations on MileBench, a benchmark encompassing 29 multimodal datasets, demonstrate CSP's effectiveness, achieving up to a 41\% performance improvement on challenging tasks like conversational embodied dialogue while reducing the KV cache budget by 13.6\%. The code is available at https://github.com/TerryPei/CSP

[Arxiv](https://arxiv.org/abs/2412.04652)