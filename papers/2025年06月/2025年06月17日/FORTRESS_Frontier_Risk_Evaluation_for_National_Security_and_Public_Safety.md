# FORTRESS：前沿风险评估，守护国家安全与公共安全。

发布时间：2025年06月17日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在国家安全与公共安全（NSPS）领域的应用，特别是评估模型的防护机制和潜在风险。它引入了FORTRESS数据集，用于测试模型在对抗性提示下的表现，属于LLM的应用层面研究。` `国家安全`

> FORTRESS: Frontier Risk Evaluation for National Security and Public Safety

# 摘要

> 大型语言模型（LLMs）的迅猛发展带来了既能威胁也能增强国家安全与公共安全（NSPS）的双重能力。模型内置了防护机制，旨在防范与NSPS相关的潜在滥用，同时确保善意用户仍能获取有益信息。然而，现有的评估基准往往未能以客观、稳健的方式检验这些防护机制在应对潜在NSPS风险时的稳固性。我们推出了FORTRESS：一个包含500个专家精心设计的对抗性提示的数据集，每个提示配有4-7个基于实例的二进制问题评分标准，适用于3个领域的自动化评估（仅限非机密信息）：化学、生物、放射性、核与爆炸物（CBRNE），政治暴力与恐怖主义，以及刑事与金融非法活动，共计10个子类别。每个提示-评分标准组合均配有对应的良性版本，用于检测模型的过度拒绝现象。对前沿LLMs防护机制的评估揭示了潜在风险与模型实用性之间的复杂权衡：Claude-3.5-Sonnet展现出较低的平均风险评分（ARS）（100分中的14.09分），但其过度拒绝评分（ORS）高达21.8分；相比之下，Gemini 2.5 Pro的过度拒绝评分仅为1.4分，但平均潜在风险却高达66.29分。Deepseek-R1以78.05分的ARS居首，但其ORS仅为0.06分。像o1这样的模型则在潜在风险与过度拒绝之间实现了更为均衡的权衡（ARS为21.69分，ORS为5.2分）。为了让政策制定者和研究人员清晰掌握模型的潜在风险，我们已将FORTRESS数据集公开发布，访问链接为https://huggingface.co/datasets/ScaleAI/fortress_public。同时，我们还保留了一个私有数据集用于内部评估。

> The rapid advancement of large language models (LLMs) introduces dual-use capabilities that could both threaten and bolster national security and public safety (NSPS). Models implement safeguards to protect against potential misuse relevant to NSPS and allow for benign users to receive helpful information. However, current benchmarks often fail to test safeguard robustness to potential NSPS risks in an objective, robust way. We introduce FORTRESS: 500 expert-crafted adversarial prompts with instance-based rubrics of 4-7 binary questions for automated evaluation across 3 domains (unclassified information only): Chemical, Biological, Radiological, Nuclear and Explosive (CBRNE), Political Violence & Terrorism, and Criminal & Financial Illicit Activities, with 10 total subcategories across these domains. Each prompt-rubric pair has a corresponding benign version to test for model over-refusals. This evaluation of frontier LLMs' safeguard robustness reveals varying trade-offs between potential risks and model usefulness: Claude-3.5-Sonnet demonstrates a low average risk score (ARS) (14.09 out of 100) but the highest over-refusal score (ORS) (21.8 out of 100), while Gemini 2.5 Pro shows low over-refusal (1.4) but a high average potential risk (66.29). Deepseek-R1 has the highest ARS at 78.05, but the lowest ORS at only 0.06. Models such as o1 display a more even trade-off between potential risks and over-refusals (with an ARS of 21.69 and ORS of 5.2). To provide policymakers and researchers with a clear understanding of models' potential risks, we publicly release FORTRESS at https://huggingface.co/datasets/ScaleAI/fortress_public. We also maintain a private set for evaluation.

[Arxiv](https://arxiv.org/abs/2506.14922)