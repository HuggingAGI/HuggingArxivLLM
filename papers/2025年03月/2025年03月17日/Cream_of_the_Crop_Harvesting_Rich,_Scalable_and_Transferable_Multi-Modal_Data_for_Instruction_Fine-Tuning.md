# 萃取精华：海量可迁移多模态数据助力指令微调

发布时间：2025年03月17日

`LLM应用

理由：这篇论文主要讨论了在多模态大型语言模型（MLLMs）中如何高效稳健地获取指令数据，并提出了一种新的数据选择方法mmSSR。论文的重点在于数据整理和选择策略，以及如何通过这些策略提升模型的性能，属于LLM的应用层面。` `多模态` `数据工程`

> Cream of the Crop: Harvesting Rich, Scalable and Transferable Multi-Modal Data for Instruction Fine-Tuning

# 摘要

> 预训练大型语言模型（LLMs）在微调（SFT）阶段仅需极小监督这一假设，近期得到了数据整理与选择研究的有力支持（Zhou et al., 2024）。然而，由于模型易受实验设置和验证协议的影响，其稳定性和泛化能力受损，未能超越随机采样（Diddee & Ippolito, 2024; Xia et al., 2024b）。基于LLMs构建的多模态LLMs（MLLMs），结合海量令牌和数据来源的高度异质性，进一步凸显了数据选择的重要性和复杂性。

为高效稳健地获取多模态指令数据，我们重新定义了质量指标的粒度，将其分解为14项视觉语言相关能力，并引入多模态丰富评分器来评估每条数据候选的能力。为促进多样性，我们以对齐阶段的内在目标为依据，将交互风格作为多样性指标，并借助多模态丰富样式器识别数据指令模式。通过这种方式，我们的多模态丰富评分器和样式器（mmSSR）确保了高分信息以多样化形式传递给用户。mmSSR无需基于嵌入的聚类或贪心采样，能高效扩展至数百万数据，适应不同预算约束，支持通用或特定能力的定制化获取，并助力无需训练即可向新领域推广的整理工作。

经过10多种实验设置的验证，借助14项多模态基准测试，我们展示了相较于随机采样、基线策略及现有最优选择方法的一致性提升。仅使用260万数据中的30%，即78万数据，即可达到99.1%的完整性能。

> The hypothesis that pretrained large language models (LLMs) necessitate only minimal supervision during the fine-tuning (SFT) stage (Zhou et al., 2024) has been substantiated by recent advancements in data curation and selection research. However, their stability and generalizability are compromised due to the vulnerability to experimental setups and validation protocols, falling short of surpassing random sampling (Diddee & Ippolito, 2024; Xia et al., 2024b). Built upon LLMs, multi-modal LLMs (MLLMs), combined with the sheer token volume and heightened heterogeneity of data sources, amplify both the significance and complexity of data selection.
  To harvest multi-modal instructional data in a robust and efficient manner, we re-define the granularity of the quality metric by decomposing it into 14 vision-language-related capabilities, and introduce multi-modal rich scorers to evaluate the capabilities of each data candidate. To promote diversity, in light of the inherent objective of the alignment stage, we take interaction style as diversity indicator and use a multi-modal rich styler to identify data instruction patterns. In doing so, our multi-modal rich scorers and styler (mmSSR) guarantee that high-scoring information is conveyed to users in diversified forms. Free from embedding-based clustering or greedy sampling, mmSSR efficiently scales to millions of data with varying budget constraints, supports customization for general or specific capability acquisition, and facilitates training-free generalization to new domains for curation. Across 10+ experimental settings, validated by 14 multi-modal benchmarks, we demonstrate consistent improvements over random sampling, baseline strategies and state-of-the-art selection methods, achieving 99.1% of full performance with only 30% of the 2.6M data.

[Arxiv](https://arxiv.org/abs/2503.13383)