# HIPPO：结合混合模式偏好优化，提升大型语言模型的表格理解能力

发布时间：2025年02月24日

`LLM应用` `表格处理` `多模态模型`

> HIPPO: Enhancing the Table Understanding Capability of Large Language Models through Hybrid-Modal Preference Optimization

# 摘要

> 表格数据蕴含丰富的结构化语义，在信息组织与处理中扮演着关键角色。为了更好地捕捉这些结构化语义，本文提出了HybrId-modal Preference oPtimizatiOn (HIPPO)模型。该模型通过文本与图像双模态表征表格，并优化多模态大语言模型（MLLMs），使其能够从多模态中有效学习更全面的表格信息。具体而言，HIPPO从混合模态的表格表示中采样模型响应，并设计了一种模态一致性的采样策略，以提升响应多样性并缓解DPO训练中的模态偏差。在表格问答和事实核查任务上的实验结果证实了HIPPO的有效性，相较于现有表格推理模型，性能提升了4%。进一步分析表明，HIPPO不仅强化了基于单模态表格表示的推理能力，还能够从不同模态表征中提取关键且独特的语义信息。所有数据和代码均可在https://github.com/NEUIR/HIPPO获取。

> Tabular data contains rich structural semantics and plays a crucial role in organizing and manipulating information. To better capture these structural semantics, this paper introduces the HybrId-modal Preference oPtimizatiOn (HIPPO) model, which represents tables using both text and image, and optimizes MLLMs to effectively learn more comprehensive table information from these multiple modalities. Specifically, HIPPO samples model responses from hybrid-modal table representations and designs a modality-consistent sampling strategy to enhance response diversity and mitigate modality bias during DPO training. Experimental results on table question answering and table fact verification tasks demonstrate the effectiveness of HIPPO, achieving a 4% improvement over various table reasoning models. Further analysis reveals that HIPPO not only enhances reasoning abilities based on unimodal table representations but also facilitates the extraction of crucial and distinct semantics from different modal representations. All data and codes are available at https://github.com/NEUIR/HIPPO.

[Arxiv](https://arxiv.org/abs/2502.17315)