# # 基于数据约束的训练数据生成用于去识别化

发布时间：2025年02月20日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在生成合成临床文本和训练命名实体识别（NER）模型中的应用。研究重点在于利用LLMs生成带有个人信息标识符标签的数据，并通过实验和消融研究评估其有效性。因此，这篇论文属于LLM应用类别。`

> Data-Constrained Synthesis of Training Data for De-Identification

# 摘要

> 在临床等敏感领域，由于隐私风险，难以获取大规模公开数据集。大型语言模型（LLMs）强大的生成能力为这一难题提供了合成数据集的解决方案。本研究将LLMs进行临床领域适配，生成带有个人信息标识符标签的合成临床文本，这些标签由先进的基于编码器的NER模型进行机器标注。随后，我们利用这些合成语料库训练NER模型。实验结果显示，使用合成语料库训练仅导致预测性能的小幅下降。通过系统性的消融研究——基于瑞典语和西班牙语数据——我们深入探究了这一方法的局限性。分析表明，较小规模的数据集可能足以支持LLMs的领域适配以实现数据合成。然而，这一方法的效果几乎完全依赖于使用原始数据训练的机器标注NER模型的表现。

> Many sensitive domains -- such as the clinical domain -- lack widely available datasets due to privacy risks. The increasing generative capabilities of large language models (LLMs) have made synthetic datasets a viable path forward. In this study, we domain-adapt LLMs to the clinical domain and generate synthetic clinical texts that are machine-annotated with tags for personally identifiable information using capable encoder-based NER models. The synthetic corpora are then used to train synthetic NER models. The results show that training NER models using synthetic corpora incurs only a small drop in predictive performance. The limits of this process are investigated in a systematic ablation study -- using both Swedish and Spanish data. Our analysis shows that smaller datasets can be sufficient for domain-adapting LLMs for data synthesis. Instead, the effectiveness of this process is almost entirely contingent on the performance of the machine-annotating NER models trained using the original data.

[Arxiv](https://arxiv.org/abs/2502.14677)