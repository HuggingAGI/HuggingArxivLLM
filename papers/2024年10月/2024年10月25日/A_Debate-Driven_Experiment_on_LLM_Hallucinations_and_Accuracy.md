# 一场由辩论驱动的关于 LLM 幻觉与准确性的实验

发布时间：2024年10月25日

`LLM应用` `模型评估`

> A Debate-Driven Experiment on LLM Hallucinations and Accuracy

# 摘要

> 大型语言模型（LLMs）在生成连贯且贴合语境的文本上取得了一定成就，然而它们仍易陷入一个名为“幻觉”的重大难题：产出未获输入或外部知识支撑的信息。此前为减轻幻觉所做的努力，聚焦于诸如在优质数据集上对模型进行微调、引入事实核查机制以及开发对抗训练方法等技术。尽管这些方式展现出了一定成效，但它们通常只在单个模型输出的层面处理问题，对模型间相互作用对幻觉的影响未作探究。本研究借助一个新颖的实验框架来探究 LLMs 中的幻觉现象，在该框架下，多个 GPT-4o-Mini 模型实例依据 TruthfulQA 数据集中的问题展开类似辩论的交互。其中一个模型被特意要求生成看似合理实则错误的答案，而其他模型则需如实作答。此实验旨在评估一个模型引入的错误信息能否促使如实回答的大多数模型更好地论证其推理，从而提升在 TruthfulQA 基准测试中的表现。研究发现，模型间的相互作用能够为提升 LLM 输出的准确性和稳健性提供宝贵的见解，对现有的缓解策略形成补充。

> Large language models (LLMs) have achieved a degree of success in generating coherent and contextually relevant text, yet they remain prone to a significant challenge known as hallucination: producing information that is not substantiated by the input or external knowledge. Previous efforts to mitigate hallucinations have focused on techniques such as fine-tuning models on high-quality datasets, incorporating fact-checking mechanisms, and developing adversarial training methods. While these approaches have shown some promise, they often address the issue at the level of individual model outputs, leaving unexplored the effects of inter-model interactions on hallucination. This study investigates the phenomenon of hallucination in LLMs through a novel experimental framework where multiple instances of GPT-4o-Mini models engage in a debate-like interaction prompted with questions from the TruthfulQA dataset. One model is deliberately instructed to generate plausible but false answers while the other models are asked to respond truthfully. The experiment is designed to assess whether the introduction of misinformation by one model can challenge the truthful majority to better justify their reasoning, improving performance on the TruthfulQA benchmark. The findings suggest that inter-model interactions can offer valuable insights into improving the accuracy and robustness of LLM outputs, complementing existing mitigation strategies.

[Arxiv](https://arxiv.org/abs/2410.19485)