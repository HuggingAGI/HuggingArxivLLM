# # HyperCLOVA X THINK 技术报告

发布时间：2025年06月27日

`LLM应用`

> HyperCLOVA X THINK Technical Report

# 摘要

> 我们很高兴推出HyperCLOVA X系列中首个专注于推理的大型语言模型——HyperCLOVA X THINK。它基于约6万亿高质量的韩语和英语tokens进行预训练，并结合了针对性的合成韩语数据。该模型采用计算与内存平衡的Peri-LN Transformer架构，通过μP进行扩展，并经过三阶段课程预训练，将上下文窗口扩展至128K tokens。同时，它通过监督微调和可验证奖励的强化学习进行后训练，支持详细推理和简洁回答两种模式。在韩国特定的基准测试（如KMMLU、CSAT、KoBALT-700、HAERAE-1.0和KoBigBench）中，HyperCLOVA X THINK与同规模模型相比表现优异，同时保持了双语一致性和翻译质量。此外，其视觉增强版本在KCSAT STEM基准上甚至超越了GPT-4.1，这一切均在远低于现有同规模模型的训练计算量下实现。我们还开发了一种剪枝和蒸馏技术，即将应用于HyperCLOVA X THINK，以打造一个开源且商业友好的基础模型。总体而言，HyperCLOVA X THINK不仅为韩国AI创新提供了坚实的技术基础，也为全球研究社区贡献了宝贵的资源。

> We introduce HyperCLOVA X THINK, the first reasoning-focused large language model in the HyperCLOVA X family, pre-trained on roughly $6$ trillion high-quality Korean, and English tokens, augmented with targeted synthetic Korean data. It was implemented as a compute-memory-balanced Peri-LN Transformer scaled with $μ$P, pre-trained through a three-stage curriculum that expands the context window to $128$K tokens, and post-trained via supervised fine-tuning with Reinforcement Learning from Verifiable Rewards supports both detailed rationale and concise-answer modes. It delivers competitive performance against similarly sized models on Korea-focused benchmarks such as KMMLU, CSAT, KoBALT-700, HAERAE-1.0, and KoBigBench, while preserving robust bilingual consistency and translation quality. In addition, a vision-augmented variant matches or exceeds GPT-4.1 on the KCSAT STEM benchmark, all of which are achieved with substantially lower training compute than existing models of similar sizes. We also present a pruning and distillation technique that will soon be applied to HyperCLOVA X THINK for an open-source and business-friendly foundation model. Altogether, these capabilities position HyperCLOVA X THINK as a robust foundation for Korean AI innovation and a valuable resource for the global research community.

[Arxiv](https://arxiv.org/abs/2506.22403)