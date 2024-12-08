# 反向思考让大型语言模型成为更强的推理者

发布时间：2024年11月29日

`LLM应用` `语言模型`

> Reverse Thinking Makes LLMs Stronger Reasoners

# 摘要

> 摘要：逆向思维在人类推理中至关重要。人类不但能从问题推导出解决方案，还能反向操作，即从解决方案推理回问题。这通常能提升整体推理表现，因为它能在正向和逆向思维之间进行一致性校验。为让大型语言模型（LLMs）具备逆向思维能力，我们推出了逆向增强思维（RevThink），这是一个由数据增强和学习目标构成的框架。在RevThink中，我们通过收集教师模型的结构化正向-逆向推理来扩充数据集，包含：（1）原始问题，（2）正向推理，（3）逆向问题，（4）逆向推理。接着，我们运用三个目标以多任务学习的方式训练较小的学生模型：（a）依据问题生成正向推理，（b）依据问题生成逆向问题，（c）依据逆向问题生成逆向推理。针对涵盖常识、数学和逻辑推理的12个数据集所做的实验显示，学生模型的零样本性能平均提升了13.53%，比最强的知识蒸馏基线提升了6.84%。此外，我们的方法体现出样本效率——仅使用训练数据中10%的正确正向推理，就胜过在十倍以上正向推理上训练的标准微调方法。RevThink在分布外的保留数据集上也展现出强大的泛化能力。

> 
Abstract:Reverse thinking plays a crucial role in human reasoning. Humans can reason not only from a problem to a solution but also in reverse, i.e., start from the solution and reason towards the problem. This often enhances overall reasoning performance as it enables consistency checks between their forward and backward thinking. To enable Large Language Models (LLMs) to perform reverse thinking, we introduce Reverse-Enhanced Thinking (RevThink), a framework composed of data augmentation and learning objectives. In RevThink, we augment the dataset by collecting structured forward-backward reasoning from a teacher model, consisting of: (1) the original question, (2) forward reasoning, (3) backward question, and (4) backward reasoning. We then employ three objectives to train a smaller student model in a multi-task learning fashion: (a) generate forward reasoning from a question, (b) generate a backward question from a question, and (c) generate backward reasoning from the backward question. Experiments across 12 datasets covering commonsense, math, and logical reasoning show an average 13.53% improvement over the student model's zero-shot performance and a 6.84% improvement over the strongest knowledge distillation baselines. Moreover, our method demonstrates sample efficiency -- using only 10% of the correct forward reasoning from the training data, it outperforms a standard fine-tuning method trained on 10x more forward reasoning. RevThink also exhibits strong generalization to out-of-distribution held-out datasets.
    

[Arxiv](https://arxiv.org/pdf/2411.19865)