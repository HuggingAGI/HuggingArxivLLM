# 多模态隐喻理解之路：中文隐喻映射识别数据集与模型

发布时间：2025年01月04日

`LLM应用

**理由**：这篇论文主要关注的是自然语言处理（NLP）中的隐喻理解问题，特别是通过开发中文多模态隐喻广告数据集（CM3D）和提出基于链式思维（CoT）提示的隐喻映射识别模型（CPMMIM）来推动非英语语言中的隐喻理解研究。虽然论文涉及了隐喻的认知复杂性和映射过程，但其核心是通过LLM（大型语言模型）的应用来解决NLP中的具体问题，即隐喻映射的识别和理解。因此，将其分类为LLM应用是合适的。`

> Towards Multimodal Metaphor Understanding: A Chinese Dataset and Model for Metaphor Mapping Identification

# 摘要

> # 摘要
隐喻在人类交流中至关重要，但其认知复杂性使其成为自然语言处理（NLP）中的一大挑战。根据概念隐喻理论（CMT），隐喻将目标域映射到源域，理解这种映射是把握隐喻本质的关键。现有NLP研究多聚焦于隐喻检测和情感分析，但对源域与目标域映射的复杂过程关注不足。此外，非英语多模态隐喻资源在文献中鲜有提及，阻碍了对隐喻解释关键要素的深入理解。为此，我们开发了中文多模态隐喻广告数据集（CM3D），包含特定目标域和源域的注释，旨在推动非英语语言中的隐喻理解研究。我们还提出了基于链式思维（CoT）提示的隐喻映射识别模型（CPMMIM），模拟人类认知过程，通过双层优化（BLO）将其视为分层识别问题，实现更准确、可解释的隐喻映射。实验结果验证了CPMMIM的有效性，展示了其在NLP隐喻理解中的潜力。数据集和代码均已公开，以促进该领域的进一步发展。

> Metaphors play a crucial role in human communication, yet their comprehension remains a significant challenge for natural language processing (NLP) due to the cognitive complexity involved. According to Conceptual Metaphor Theory (CMT), metaphors map a target domain onto a source domain, and understanding this mapping is essential for grasping the nature of metaphors. While existing NLP research has focused on tasks like metaphor detection and sentiment analysis of metaphorical expressions, there has been limited attention to the intricate process of identifying the mappings between source and target domains. Moreover, non-English multimodal metaphor resources remain largely neglected in the literature, hindering a deeper understanding of the key elements involved in metaphor interpretation. To address this gap, we developed a Chinese multimodal metaphor advertisement dataset (namely CM3D) that includes annotations of specific target and source domains. This dataset aims to foster further research into metaphor comprehension, particularly in non-English languages. Furthermore, we propose a Chain-of-Thought (CoT) Prompting-based Metaphor Mapping Identification Model (CPMMIM), which simulates the human cognitive process for identifying these mappings. Drawing inspiration from CoT reasoning and Bi-Level Optimization (BLO), we treat the task as a hierarchical identification problem, enabling more accurate and interpretable metaphor mapping. Our experimental results demonstrate the effectiveness of CPMMIM, highlighting its potential for advancing metaphor comprehension in NLP. Our dataset and code are both publicly available to encourage further advancements in this field.

[Arxiv](https://arxiv.org/abs/2501.02434)