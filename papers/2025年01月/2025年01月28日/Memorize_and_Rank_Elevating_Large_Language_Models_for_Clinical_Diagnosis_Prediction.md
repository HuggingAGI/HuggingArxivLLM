# 记忆与排序：优化大型语言模型在临床诊断预测中的应用

发布时间：2025年01月28日

`LLM应用

**理由**：该论文摘要描述了如何利用大型语言模型（LLMs）来改进临床诊断预测模型，具体提出了MERA模型，通过自然语言知识与医疗实践的结合来解决临床诊断中的挑战。这属于将LLM应用于特定领域（医疗诊断）的实际问题，因此分类为“LLM应用”。` `临床诊断`

> Memorize and Rank: Elevating Large Language Models for Clinical Diagnosis Prediction

# 摘要

> # 摘要
临床诊断预测模型通过分析患者病史，旨在早期发现潜在疾病，促进及时干预并改善预后。然而，患者数据的稀缺性和庞大的疾病候选空间常常为模型开发带来挑战。目前，利用大型语言模型（LLMs）封装临床决策过程的探索仍有限。我们提出了MERA模型，它将自然语言知识与医疗实践相结合，通过分层对比学习缓解大决策空间问题，并通过微调实现自然语言临床知识与医疗代码的融合。在MIMIC-III和IV数据集上的实验表明，MERA不仅达到了最先进的诊断预测性能，还显著提升了生成式LMs的诊断能力。

> Clinical diagnosis prediction models, when provided with a patient's medical history, aim to detect potential diseases early, facilitating timely intervention and improving prognostic outcomes. However, the inherent scarcity of patient data and large disease candidate space often pose challenges in developing satisfactory models for this intricate task. The exploration of leveraging Large Language Models (LLMs) for encapsulating clinical decision processes has been limited. We introduce MERA, a clinical diagnosis prediction model that bridges pertaining natural language knowledge with medical practice. We apply hierarchical contrastive learning on a disease candidate ranking list to alleviate the large decision space issue. With concept memorization through fine-tuning, we bridge the natural language clinical knowledge with medical codes. Experimental results on MIMIC-III and IV datasets show that MERA achieves the state-of-the-art diagnosis prediction performance and dramatically elevates the diagnosis prediction capabilities of generative LMs.

[Arxiv](https://arxiv.org/abs/2501.17326)