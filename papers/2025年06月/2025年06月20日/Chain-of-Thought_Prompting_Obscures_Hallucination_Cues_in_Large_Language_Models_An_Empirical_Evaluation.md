# 链式思维提示模糊大型语言模型中的幻觉线索：实证评估

发布时间：2025年06月20日

`LLM应用

摘要分析：论文探讨了链式思维（CoT）提示在缓解大型语言模型幻觉现象中的应用及其对幻觉检测的影响，属于LLM的应用层面研究。` `人工智能`

> Chain-of-Thought Prompting Obscures Hallucination Cues in Large Language Models: An Empirical Evaluation

# 摘要

> 大型语言模型（LLMs）常会出现	extit{幻觉}现象，即在响应提示时生成事实错误或语义无关的内容。链式思维（CoT）提示通过鼓励逐步推理来缓解幻觉现象，但其对幻觉检测的影响尚未被充分探索。为填补这一研究空白，我们开展了一项系统性的实证评估。首先，通过初步实验，我们发现CoT推理显著影响了LLM的内部状态和标记概率分布。在此基础上，我们评估了不同CoT提示方法对主流幻觉检测方法的影响，涵盖指令微调和推理导向的LLM。具体而言，我们分析了三个关键维度：幻觉评分分布的变化、检测准确率的波动以及检测置信度的转变。研究发现，虽然CoT提示有助于减少幻觉发生频率，但它也倾向于模糊用于检测的关键信号，削弱了多种检测方法的有效性。本研究揭示了推理使用中一个被忽视的权衡问题。代码已公开发布于：https://anonymous.4open.science/r/cot-hallu-detect.

> Large Language Models (LLMs) often exhibit \textit{hallucinations}, generating factually incorrect or semantically irrelevant content in response to prompts. Chain-of-Thought (CoT) prompting can mitigate hallucinations by encouraging step-by-step reasoning, but its impact on hallucination detection remains underexplored. To bridge this gap, we conduct a systematic empirical evaluation. We begin with a pilot experiment, revealing that CoT reasoning significantly affects the LLM's internal states and token probability distributions. Building on this, we evaluate the impact of various CoT prompting methods on mainstream hallucination detection methods across both instruction-tuned and reasoning-oriented LLMs. Specifically, we examine three key dimensions: changes in hallucination score distributions, variations in detection accuracy, and shifts in detection confidence. Our findings show that while CoT prompting helps reduce hallucination frequency, it also tends to obscure critical signals used for detection, impairing the effectiveness of various detection methods. Our study highlights an overlooked trade-off in the use of reasoning. Code is publicly available at: https://anonymous.4open.science/r/cot-hallu-detect.

[Arxiv](https://arxiv.org/abs/2506.17088)