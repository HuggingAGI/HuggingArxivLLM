# # 从微调大型语言模型中基于差异化的专有数据提取方法

发布时间：2025年06月19日

`LLM应用` `监督微调` `模型安全`

> Differentiation-Based Extraction of Proprietary Data from Fine-Tuned LLMs

# 摘要

> 领域特定且与人类对齐的大型语言模型（LLMs）需求激增，推动了监督微调技术（SFT）的广泛应用。SFT数据集中的指令-响应对具有极高价值，使其成为数据提取的理想目标。本研究首次深入探讨了这一关键问题。我们首先对问题进行形式化定义，随后基于SFT数据的独特属性，系统分析了各种攻击目标、类型及其变体。通过对直接提取行为的深入研究，我们开发了一种专门针对SFT模型的新型提取方法——差异化数据提取（DDE），该方法巧妙利用了微调模型的置信水平及其与预训练模型的行为差异。通过跨领域、跨场景的广泛实验，我们成功验证了DDE在SFT数据提取中的可行性。实验结果表明，DDE在所有攻击设置下均显著优于现有提取基线。为应对这一新型攻击，我们提出了一种创新的防御机制，能够在最小影响模型性能的前提下有效缓解DDE攻击。本研究不仅揭示了微调LLMs中隐藏的数据泄露风险，更为开发更安全的模型提供了重要启示。


> The increasing demand for domain-specific and human-aligned Large Language Models (LLMs) has led to the widespread adoption of Supervised Fine-Tuning (SFT) techniques. SFT datasets often comprise valuable instruction-response pairs, making them highly valuable targets for potential extraction. This paper studies this critical research problem for the first time. We start by formally defining and formulating the problem, then explore various attack goals, types, and variants based on the unique properties of SFT data in real-world scenarios. Based on our analysis of extraction behaviors of direct extraction, we develop a novel extraction method specifically designed for SFT models, called Differentiated Data Extraction (DDE), which exploits the confidence levels of fine-tuned models and their behavioral differences from pre-trained base models. Through extensive experiments across multiple domains and scenarios, we demonstrate the feasibility of SFT data extraction using DDE. Our results show that DDE consistently outperforms existing extraction baselines in all attack settings. To counter this new attack, we propose a defense mechanism that mitigates DDE attacks with minimal impact on model performance. Overall, our research reveals hidden data leak risks in fine-tuned LLMs and provides insights for developing more secure models.

[Arxiv](https://arxiv.org/abs/2506.17353)