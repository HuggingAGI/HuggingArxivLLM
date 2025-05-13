# 通过提示工程实现无需训练的非侵入式负荷监测

发布时间：2025年05月09日

`LLM应用` `智能电网`

> Prompting Large Language Models for Training-Free Non-Intrusive Load Monitoring

# 摘要

> 非侵入式负荷监测（NILM）的目标是将家庭整体用电量分解为各个家电的用电情况，从而实现更高效的能源管理。虽然深度学习推动了NILM的发展，但其仍面临对标注数据的依赖、泛化能力有限以及缺乏可解释性等挑战。本文中，我们提出了首个基于提示的NILM框架，该框架利用大型语言模型（LLMs）的上下文学习能力。我们设计并评估了结合家电特征、时间戳、上下文信息以及代表性时间序列示例的提示策略，实验基于REDD数据集进行。通过优化提示，LLMs在未见家庭中实现了平均F1分数0.676的高水平状态检测准确率，并展现了无需微调的强健泛化能力。此外，LLMs通过提供清晰、可读的人类语言解释，显著提升了预测的可解释性。我们的研究结果表明，LLMs能够有效减少数据需求，增强适应性，并在NILM应用中实现透明化的能源分解。

> Non-intrusive Load Monitoring (NILM) aims to disaggregate aggregate household electricity consumption into individual appliance usage, enabling more effective energy management. While deep learning has advanced NILM, it remains limited by its dependence on labeled data, restricted generalization, and lack of interpretability. In this paper, we introduce the first prompt-based NILM framework that leverages Large Language Models (LLMs) with in-context learning. We design and evaluate prompt strategies that integrate appliance features, timestamps and contextual information, as well as representative time-series examples, using the REDD dataset. With optimized prompts, LLMs achieve competitive state detection accuracy, reaching an average F1-score of 0.676 on unseen households, and demonstrate robust generalization without the need for fine-tuning. LLMs also enhance interpretability by providing clear, human-readable explanations for their predictions. Our results show that LLMs can reduce data requirements, improve adaptability, and provide transparent energy disaggregation in NILM applications.

[Arxiv](https://arxiv.org/abs/2505.06330)