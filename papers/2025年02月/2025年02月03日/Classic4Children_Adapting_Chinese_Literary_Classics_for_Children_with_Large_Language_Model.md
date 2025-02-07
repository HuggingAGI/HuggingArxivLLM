# Classic4Children: 用大型语言模型为中国儿童量身定制中国文学经典

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何通过增强大型语言模型（LLM）来适应儿童阅读偏好，从而将中国文学经典改编为适合儿童阅读的文本。论文提出的方法InstructChild涉及对LLM的指令调优、可读性指标设计以及推理策略的改进，这些都是LLM在实际应用中的具体应用场景。因此，这篇论文应归类为LLM应用。`

> Classic4Children: Adapting Chinese Literary Classics for Children with Large Language Model

# 摘要

> # 摘要
中国文学经典蕴含深厚的文化和教育价值，深刻揭示了道德、历史与人性。然而，这些作品常以文言文和复杂叙事呈现，儿童难以理解。为此，我们提出了儿童友好文学改编（CLA）任务，旨在将经典作品转化为适合儿童阅读的文本。然而，现有的大型语言模型（LLMs）往往忽略了儿童的阅读偏好（如生动的角色刻画、简洁的叙事结构和适当的可读性），这为CLA带来了挑战。本文提出了一种名为InstructChild的方法，通过增强LLM来适应这些偏好。具体而言，我们首先提取角色的个性和叙事结构，作为细粒度指令调优的补充信息；其次，设计了一个可读性指标作为奖励，使LLM的输出更符合儿童的阅读水平；最后，在推理过程中采用前瞻解码策略，进一步提升生成文本的可读性。为支持CLA任务的评估，我们构建了Classic4Children数据集，涵盖中国四大古典小说的原始版本和儿童友好版本。实验结果表明，InstructChild显著提升了自动评估和人工评估的表现。

> Chinese literary classics hold significant cultural and educational value, offering deep insights into morality, history, and human nature. These works often include classical Chinese and complex narratives, making them difficult for children to read. To bridge this gap, we introduce a child-friendly literary adaptation (CLA) task to adapt the Chinese literary classic into engaging and accessible text for children. However, recent large language models (LLMs) overlook children's reading preferences (\ie, vivid character portrayals, concise narrative structures, and appropriate readability), which poses challenges in CLA. In this paper, we propose a method called InstructChild, which augments the LLM with these preferences for adaptation. Specifically, we first obtain the characters' personalities and narrative structure as additional information for fine-grained instruction tuning. Then, we devise a readability metric as the reward to align the LLM with the children's reading level. Finally, a lookahead decoding strategy is applied to improve the readability of the generated text during inference. To support the evaluation of CLA task, we construct the Classic4Children dataset, which comprises both the original and child-friendly versions of the Four Great Classical Novels of Chinese literature. Experimental results show that our InstructChild significantly improves automatic and human evaluation performance.

[Arxiv](https://arxiv.org/abs/2502.01090)