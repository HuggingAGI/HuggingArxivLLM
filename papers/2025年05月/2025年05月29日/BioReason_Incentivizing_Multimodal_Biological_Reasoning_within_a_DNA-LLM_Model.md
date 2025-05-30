# # BioReason: 驱动 DNA-LLM 模型实现多模态生物推理的激励机制

发布时间：2025年05月29日

`LLM应用` `生物学` `生物信息学`

> BioReason: Incentivizing Multimodal Biological Reasoning within a DNA-LLM Model

# 摘要

> 从复杂基因组数据中解锁深入且可解释的生物推理是科学发现面临的重要AI挑战。当前DNA基础模型虽在序列表示上表现出色，但在多步推理和生物直观解释方面仍有不足。我们推出BioReason，这一开创性架构首次将DNA基础模型与大型语言模型（LLM）深度整合，使LLM能够直接处理基因组信息，开创了多模态生物理解的新模式。通过监督微调和强化学习，BioReason实现了逻辑连贯的多步推理。在疾病通路预测等基准测试中，BioReason较单模态基线平均提升15%。它不仅推理未知生物实体，还通过可解释的分步轨迹阐述决策，为AI在生物学中的应用带来突破，助力机制洞察和假设生成。项目资源可在GitHub获取。

> Unlocking deep, interpretable biological reasoning from complex genomic data is a major AI challenge hindering scientific discovery. Current DNA foundation models, despite strong sequence representation, struggle with multi-step reasoning and lack inherent transparent, biologically intuitive explanations. We introduce BioReason, a pioneering architecture that, for the first time, deeply integrates a DNA foundation model with a Large Language Model (LLM). This novel connection enables the LLM to directly process and reason with genomic information as a fundamental input, fostering a new form of multimodal biological understanding. BioReason's sophisticated multi-step reasoning is developed through supervised fine-tuning and targeted reinforcement learning, guiding the system to generate logical, biologically coherent deductions. On biological reasoning benchmarks including KEGG-based disease pathway prediction - where accuracy improves from 88% to 97% - and variant effect prediction, BioReason demonstrates an average 15% performance gain over strong single-modality baselines. BioReason reasons over unseen biological entities and articulates decision-making through interpretable, step-by-step biological traces, offering a transformative approach for AI in biology that enables deeper mechanistic insights and accelerates testable hypothesis generation from genomic data. Data, code, and checkpoints are publicly available at https://github.com/bowang-lab/BioReason

[Arxiv](https://arxiv.org/abs/2505.23579)