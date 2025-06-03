# 基于输出层融合技术与校准模型的大型语言模型排毒方法

发布时间：2025年06月01日

`LLM应用` `内容安全`

> Detoxification of Large Language Models through Output-layer Fusion with a Calibration Model

# 摘要

> 现有大型语言模型（LLM）的净化方法通常依赖于大规模无毒数据训练、设计提示指令生成安全内容或修改模型参数去除有毒信息，这些方法计算成本高昂、缺乏鲁棒性，且常会损害模型的流畅性和上下文理解能力。本文提出了一种简单而有效的净化方法，利用紧凑的预训练校准模型，通过轻量级干预引导目标LLM的生成管道完成净化过程。校准模型从无毒数据中学习净化后的嵌入空间，有效引导LLM远离有害内容生成。该方法仅需一次训练即可无缝应用于多个LLM，同时保持流畅性和上下文理解能力。实验结果表明，我们的方法在减少毒性的同时，仍能保持合理的内容表达能力。

> Existing approaches for Large language model (LLM) detoxification generally rely on training on large-scale non-toxic or human-annotated preference data, designing prompts to instruct the LLM to generate safe content, or modifying the model parameters to remove toxic information, which are computationally expensive, lack robustness, and often compromise LLMs' fluency and contextual understanding. In this paper, we propose a simple yet effective approach for LLM detoxification, which leverages a compact, pre-trained calibration model that guides the detoxification process of a target LLM via a lightweight intervention in its generation pipeline. By learning a detoxified embedding space from non-toxic data, the calibration model effectively steers the LLM away from generating harmful content. This approach only requires a one-time training of the calibration model that is able to be seamlessly applied to multiple LLMs without compromising fluency or contextual understanding. Experiment results on the benchmark dataset demonstrate that our approach reduces toxicity while maintaining reasonable content expression.

[Arxiv](https://arxiv.org/abs/2506.01266)