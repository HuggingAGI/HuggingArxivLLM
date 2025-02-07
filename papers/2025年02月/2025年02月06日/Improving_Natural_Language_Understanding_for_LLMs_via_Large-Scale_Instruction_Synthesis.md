# 通过大规模指令合成增强LLMs的自然语言理解能力

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了如何通过构建一个大规模的合成指令语料库（Hum）来提升大型语言模型（LLMs）在自然语言理解（NLU）任务中的表现。论文的核心内容集中在如何通过数据增强和任务多样性来优化LLMs的应用效果，属于LLM在实际任务中的应用研究。` `人工智能`

> Improving Natural Language Understanding for LLMs via Large-Scale Instruction Synthesis

# 摘要

> 高质量、大规模的指令对于对齐大型语言模型（LLMs）至关重要，然而，自然语言理解（NLU）领域的指令却严重匮乏。以往的研究主要集中在信息抽取（IE）上，忽略了机器阅读理解、问答和文本分类等任务。此外，数据多样性不足导致训练后的LLMs在其他NLU任务中的泛化能力下降，基础模型的通用能力也显著减弱。为此，我们提出了Hum，一个专为NLU任务设计的大规模、高质量合成指令语料库，旨在提升LLMs的NLU能力。Hum涵盖了IE（封闭式和开放式）、机器阅读理解、文本分类及指令通用任务，极大地丰富了任务多样性。我们还引入了人机协作机制来合成指令，通过结合指南、偏好规则和格式变体，进一步提升了指令的多样性。我们在5个NLU任务和28个通用能力评估数据集上进行了广泛实验，结果显示，Hum将六种LLMs的NLU能力平均提升了3.1%，且在其他通用能力上未见显著下降。

> High-quality, large-scale instructions are crucial for aligning large language models (LLMs), however, there is a severe shortage of instruction in the field of natural language understanding (NLU). Previous works on constructing NLU instructions mainly focus on information extraction (IE), neglecting tasks such as machine reading comprehension, question answering, and text classification. Furthermore, the lack of diversity in the data has led to a decreased generalization ability of trained LLMs in other NLU tasks and a noticeable decline in the fundamental model's general capabilities. To address this issue, we propose Hum, a large-scale, high-quality synthetic instruction corpus for NLU tasks, designed to enhance the NLU capabilities of LLMs. Specifically, Hum includes IE (either close IE or open IE), machine reading comprehension, text classification, and instruction generalist tasks, thereby enriching task diversity. Additionally, we introduce a human-LLMs collaborative mechanism to synthesize instructions, which enriches instruction diversity by incorporating guidelines, preference rules, and format variants. We conduct extensive experiments on 5 NLU tasks and 28 general capability evaluation datasets for LLMs. Experimental results show that Hum enhances the NLU capabilities of six LLMs by an average of 3.1\%, with no significant decline observed in other general capabilities.

[Arxiv](https://arxiv.org/abs/2502.03843)