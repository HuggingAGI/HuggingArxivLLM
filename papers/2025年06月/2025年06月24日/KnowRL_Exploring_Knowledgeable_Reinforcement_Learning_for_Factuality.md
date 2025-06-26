# KnowRL: 深入研究知识增强的强化学习，揭示其在事实性任务中的潜在能力

发布时间：2025年06月24日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）中的幻觉问题，并提出了一种新的训练方法（KnowRL），旨在改进模型的推理过程和知识边界识别。这属于对LLM本身的理论分析和改进，因此归类为LLM理论。` `问答系统`

> KnowRL: Exploring Knowledgeable Reinforcement Learning for Factuality

# 摘要

> 大型语言模型（LLMs），尤其是慢思考模型，常常因为无法准确识别知识边界而导致输出错误内容，表现出严重的幻觉现象。虽然强化学习（RL）能够提升复杂的推理能力，但其以结果为导向的奖励机制往往缺乏对推理过程的事实监督，进一步加剧了幻觉问题。为了解决慢思考模型中的幻觉问题，我们提出了知识增强的强化学习方法（KnowRL）。通过在RL训练过程中引入基于知识验证的事实性奖励，KnowRL引导模型进行基于事实的慢思考，帮助它们识别自己的知识边界。这种针对性的事实输入使模型能够学习并内化基于事实的推理策略。通过直接奖励推理步骤中对事实的遵循，KnowRL培养了更加可靠地思考过程。在三个幻觉评估数据集和两个推理评估数据集上的实验结果表明，KnowRL有效缓解了慢思考模型中的幻觉问题，同时保持了它们原有的强大推理能力。我们的代码可在https://github.com/zjunlp/KnowRL获取。

> Large Language Models (LLMs), particularly slow-thinking models, often exhibit severe hallucination, outputting incorrect content due to an inability to accurately recognize knowledge boundaries during reasoning. While Reinforcement Learning (RL) can enhance complex reasoning abilities, its outcome-oriented reward mechanism often lacks factual supervision over the thinking process, further exacerbating the hallucination problem. To address the high hallucination in slow-thinking models, we propose Knowledge-enhanced RL, KnowRL. KnowRL guides models to perform fact-based slow thinking by integrating a factuality reward, based on knowledge verification, into the RL training process, helping them recognize their knowledge boundaries. KnowRL guides models to perform fact-based slow thinking by integrating a factuality reward, based on knowledge verification, into the RL training process, helping them recognize their knowledge boundaries. This targeted factual input during RL training enables the model to learn and internalize fact-based reasoning strategies. By directly rewarding adherence to facts within the reasoning steps, KnowRL fosters a more reliable thinking process. Experimental results on three hallucination evaluation datasets and two reasoning evaluation datasets demonstrate that KnowRL effectively mitigates hallucinations in slow-thinking models while maintaining their original strong reasoning capabilities. Our code is available at https://github.com/zjunlp/KnowRL.

[Arxiv](https://arxiv.org/abs/2506.19807)