# NIRVANA：为大型语言模型压缩重新构想的结构化剪枝

发布时间：2025年09月17日

`LLM理论` `基础理论`

> NIRVANA: Structured pruning reimagined for large language models compression

# 摘要

> 大型语言模型（LLMs）的结构化剪枝通过移除整个隐藏单元实现了效率的显著提升，然而现有方法往往会导致性能大幅下降（尤其是在零样本场景下），且需要有监督微调（SFT）或适配器插入等成本高昂的恢复手段。为解决这些关键问题，我们提出了NIRVANA——一种新型剪枝方法，专门设计用于平衡即时零样本精度保留与强大的微调能力。NIRVANA利用在Adam优化动态下从神经正切核导出的一阶显著性准则，提供了一种理论严谨的剪枝策略，能够尊重模型关键的训练行为。为进一步应对结构化剪枝带来的独特挑战，NIRVANA在各层和模块（注意力模块与MLP模块）间引入了自适应稀疏分配机制，通过全局平衡的方式调整模块间的剪枝强度。此外，为缓解剪枝决策对校准数据质量的高度敏感性，我们提出了一种简单有效的基于KL散度的校准数据选择策略，以确保更可靠且与任务无关的剪枝效果。在Llama3、Qwen和T5模型上的综合实验表明，在同等稀疏度约束下，NIRVANA性能优于现有结构化剪枝方法，为LLM压缩提供了理论可靠且实用的解决方案。代码可访问https://github.com/iDEA-iSAIL-Lab-UIUC/NIRVANA获取。

> Structured pruning of large language models (LLMs) offers substantial efficiency improvements by removing entire hidden units, yet current approaches often suffer from significant performance degradation, particularly in zero-shot settings, and necessitate costly recovery techniques such as supervised fine-tuning (SFT) or adapter insertion. To address these critical shortcomings, we introduce NIRVANA, a novel pruning method explicitly designed to balance immediate zero-shot accuracy preservation with robust fine-tuning capability. Leveraging a first-order saliency criterion derived from the Neural Tangent Kernel under Adam optimization dynamics, NIRVANA provides a theoretically grounded pruning strategy that respects essential model training behaviors. To further address the unique challenges posed by structured pruning, NIRVANA incorporates an adaptive sparsity allocation mechanism across layers and modules (attention vs. MLP), which adjusts pruning intensity between modules in a globally balanced manner. Additionally, to mitigate the high sensitivity of pruning decisions to calibration data quality, we propose a simple yet effective KL divergence-based calibration data selection strategy, ensuring more reliable and task-agnostic pruning outcomes. Comprehensive experiments conducted on Llama3, Qwen, and T5 models demonstrate that NIRVANA outperforms existing structured pruning methods under equivalent sparsity constraints, providing a theoretically sound and practical approach to LLM compression. The code is available at https://github.com/iDEA-iSAIL-Lab-UIUC/NIRVANA.

[Arxiv](https://arxiv.org/abs/2509.14230)