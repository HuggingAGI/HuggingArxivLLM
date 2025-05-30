# Infi-MMR: 基于课程学习，通过分阶段强化学习解锁多模态小型语言模型的多模态推理能力

发布时间：2025年05月29日

`LLM应用` `多模态`

> Infi-MMR: Curriculum-based Unlocking Multimodal Reasoning via Phased Reinforcement Learning in Multimodal Small Language Models

# 摘要

> 近期研究显示，大型语言模型（LLMs）在推理能力方面取得了显著进展，例如DeepSeek-R1通过基于规则的强化学习显著提升了逻辑推理能力。然而，将这些成果扩展到多模态大型语言模型（MLLMs）面临重大挑战，这些挑战在多模态小语言模型（MSLMs）中尤为突出，原因在于其基础推理能力通常较弱：(1) 高质量多模态推理数据集的匮乏，(2) 视觉处理整合导致的推理能力下降，(3) 强化学习直接应用可能产生复杂但错误的推理过程的风险。为应对这些挑战，我们设计了一种新型框架Infi-MMR，通过精心设计的三阶段课程系统性地释放MSLMs的推理潜力，并提出了我们的多模态推理模型Infi-MMR-3B。第一阶段“基础推理激活”利用高质量的文本推理数据集激活并强化模型的逻辑推理能力。第二阶段“跨模态推理适配”采用带注释的多模态数据促进推理技能逐步向多模态环境迁移。第三阶段“多模态推理增强”则借助精挑细选的无注释多模态数据减轻语言偏见并推动稳健的跨模态推理。Infi-MMR-3B在多模态数学推理能力方面达到最新水平（MathVerse测试集mini达43.68%，MathVision测试集达27.04%，OlympiadBench达21.33%），同时在通用推理能力上也表现出色（MathVista测试集mini达67.2%）。

> Recent advancements in large language models (LLMs) have demonstrated substantial progress in reasoning capabilities, such as DeepSeek-R1, which leverages rule-based reinforcement learning to enhance logical reasoning significantly. However, extending these achievements to multimodal large language models (MLLMs) presents critical challenges, which are frequently more pronounced for Multimodal Small Language Models (MSLMs) given their typically weaker foundational reasoning abilities: (1) the scarcity of high-quality multimodal reasoning datasets, (2) the degradation of reasoning capabilities due to the integration of visual processing, and (3) the risk that direct application of reinforcement learning may produce complex yet incorrect reasoning processes. To address these challenges, we design a novel framework Infi-MMR to systematically unlock the reasoning potential of MSLMs through a curriculum of three carefully structured phases and propose our multimodal reasoning model Infi-MMR-3B. The first phase, Foundational Reasoning Activation, leverages high-quality textual reasoning datasets to activate and strengthen the model's logical reasoning capabilities. The second phase, Cross-Modal Reasoning Adaptation, utilizes caption-augmented multimodal data to facilitate the progressive transfer of reasoning skills to multimodal contexts. The third phase, Multimodal Reasoning Enhancement, employs curated, caption-free multimodal data to mitigate linguistic biases and promote robust cross-modal reasoning. Infi-MMR-3B achieves both state-of-the-art multimodal math reasoning ability (43.68% on MathVerse testmini, 27.04% on MathVision test, and 21.33% on OlympiadBench) and general reasoning ability (67.2% on MathVista testmini).

[Arxiv](https://arxiv.org/abs/2505.23091)