# IntrEx：一个建模教育对话参与度的数据集

发布时间：2025年09月08日

`LLM应用` `教育科技`

> IntrEx: A Dataset for Modeling Engagement in Educational Conversations

# 摘要

> 参与度和学习动力对第二语言习得至关重要，但在教育对话中持续吸引学习者的注意力一直是个难题。虽然先前研究已探究过如何让教育文本更有趣，但对于驱动对话参与度的语言特征，我们仍知之甚少。为此，我们推出了IntrEx——首个针对师生互动场景标注“趣味性”与“预期趣味性”的大型数据集。IntrEx基于师生聊天室语料库（TSCC）构建，通过新增序列级标注扩展了现有研究，使参与度研究不再局限于孤立对话轮次，而是能捕捉兴趣在长对话中的动态演变。我们采用严格的标注流程，邀请100余名第二语言学习者参与，并借鉴人类反馈强化学习（RLHF）的比较式评分方法以提高标注一致性。我们还研究了大型语言模型（LLMs）能否预测人类对趣味性的判断，结果发现：经趣味性评分微调的70亿/80亿参数LLM性能优于GPT-4o等更大规模的专有模型，这表明专用数据集在教育场景参与度建模方面潜力巨大。最后，我们分析了具体性、可理解性（可读性）、吸收度等语言与认知因素对教育对话参与度的影响机制。

> Engagement and motivation are crucial for second-language acquisition, yet maintaining learner interest in educational conversations remains a challenge. While prior research has explored what makes educational texts interesting, still little is known about the linguistic features that drive engagement in conversations. To address this gap, we introduce IntrEx, the first large dataset annotated for interestingness and expected interestingness in teacher-student interactions. Built upon the Teacher-Student Chatroom Corpus (TSCC), IntrEx extends prior work by incorporating sequence-level annotations, allowing for the study of engagement beyond isolated turns to capture how interest evolves over extended dialogues. We employ a rigorous annotation process with over 100 second-language learners, using a comparison-based rating approach inspired by reinforcement learning from human feedback (RLHF) to improve agreement. We investigate whether large language models (LLMs) can predict human interestingness judgments. We find that LLMs (7B/8B parameters) fine-tuned on interestingness ratings outperform larger proprietary models like GPT-4o, demonstrating the potential for specialised datasets to model engagement in educational settings. Finally, we analyze how linguistic and cognitive factors, such as concreteness, comprehensibility (readability), and uptake, influence engagement in educational dialogues.

[Arxiv](https://arxiv.org/abs/2509.06652)