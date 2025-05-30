# LLMs的有界理性：推理时的满意对齐

发布时间：2025年05月29日

`LLM理论` `人工智能` `对齐技术`

> Bounded Rationality for LLMs: Satisficing Alignment at Inference-Time

# 摘要

> 将大型语言模型与人类对齐充满挑战，因为偏好反馈本质上是多方面的。现有方法通常将此视为一个多目标优化问题，但往往忽视了人类实际的决策方式。研究表明，人类决策遵循满意策略——在优化主要目标的同时，确保其他目标达到可接受的阈值。为弥合这一差距，我们提出 SITAlign：一个推理时间框架，通过在满足次要标准的阈值约束下最大化主要目标，来应对对齐的多方面性质。我们通过推导基于满意推理对齐方法的次优性界限，提供了理论见解。通过在多个基准上的广泛实验，我们实证验证了 SITAlign 的性能。例如，在 PKU-SafeRLHF 数据集上，以最大化有用性为目标，同时确保无害性达到阈值，SITAlign 在有用性奖励方面，以 GPT-4 的胜平率计算，比最先进的多目标解码策略高出 22.3% 的优势，同时遵守无害性的阈值。

> Aligning large language models with humans is challenging due to the inherently multifaceted nature of preference feedback. While existing approaches typically frame this as a multi-objective optimization problem, they often overlook how humans actually make decisions. Research on bounded rationality suggests that human decision making follows satisficing strategies-optimizing primary objectives while ensuring others meet acceptable thresholds. To bridge this gap and operationalize the notion of satisficing alignment, we propose SITAlign: an inference time framework that addresses the multifaceted nature of alignment by maximizing a primary objective while satisfying threshold-based constraints on secondary criteria. We provide theoretical insights by deriving sub-optimality bounds of our satisficing based inference alignment approach. We empirically validate SITAlign's performance through extensive experimentation on multiple benchmarks. For instance, on the PKU-SafeRLHF dataset with the primary objective of maximizing helpfulness while ensuring a threshold on harmlessness, SITAlign outperforms the state-of-the-art multi objective decoding strategy by a margin of 22.3% in terms of GPT-4 win-tie rate for helpfulness reward while adhering to the threshold on harmlessness.

[Arxiv](https://arxiv.org/abs/2505.23729)