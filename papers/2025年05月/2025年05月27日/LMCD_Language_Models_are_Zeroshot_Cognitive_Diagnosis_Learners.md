# LMCD：语言模型是零样本认知诊断的学习者

发布时间：2025年05月27日

`LLM应用` `人工智能`

> LMCD: Language Models are Zeroshot Cognitive Diagnosis Learners

# 摘要

> 认知诊断（CD）已成为人工智能赋能教育中的关键任务，通过准确评估学生认知状态以支持个性化学习。然而，传统CD模型在冷启动场景中常常面临挑战，原因在于缺乏学生与练习之间的交互数据。近年来，基于自然语言处理（NLP）的方法利用预训练语言模型（PLMs）通过文本特征展现了潜力，但未能完全弥合语义理解和认知画像之间的差距。在本研究中，我们提出了一种名为语言模型作为零样本认知诊断学习者（LMCD）的新型框架，旨在通过利用大型语言模型（LLMs）来应对冷启动挑战。LMCD主要通过两个阶段进行操作：(1) 知识扩散阶段，LLMs生成练习和知识概念（KCs）的丰富内容，建立更强的语义联系；(2) 语义-认知融合阶段，LLMs利用因果注意力机制整合文本信息与学生认知状态，为学生和练习创建全面的画像。这些表示通过现成的CD模型进行高效训练。在两个真实数据集上的实验表明，LMCD在练习冷启动和领域冷启动设置下均显著超越现有最优方法。代码可在https://github.com/TAL-auroraX/LMCD公开获取

> Cognitive Diagnosis (CD) has become a critical task in AI-empowered education, supporting personalized learning by accurately assessing students' cognitive states. However, traditional CD models often struggle in cold-start scenarios due to the lack of student-exercise interaction data. Recent NLP-based approaches leveraging pre-trained language models (PLMs) have shown promise by utilizing textual features but fail to fully bridge the gap between semantic understanding and cognitive profiling. In this work, we propose Language Models as Zeroshot Cognitive Diagnosis Learners (LMCD), a novel framework designed to handle cold-start challenges by harnessing large language models (LLMs). LMCD operates via two primary phases: (1) Knowledge Diffusion, where LLMs generate enriched contents of exercises and knowledge concepts (KCs), establishing stronger semantic links; and (2) Semantic-Cognitive Fusion, where LLMs employ causal attention mechanisms to integrate textual information and student cognitive states, creating comprehensive profiles for both students and exercises. These representations are efficiently trained with off-the-shelf CD models. Experiments on two real-world datasets demonstrate that LMCD significantly outperforms state-of-the-art methods in both exercise-cold and domain-cold settings. The code is publicly available at https://github.com/TAL-auroraX/LMCD

[Arxiv](https://arxiv.org/abs/2505.21239)