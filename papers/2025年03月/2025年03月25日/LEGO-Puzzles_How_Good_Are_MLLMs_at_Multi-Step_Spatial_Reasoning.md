# 乐高拼图：多语言大模型的多步骤空间推理能力有多强？

发布时间：2025年03月25日

`LLM应用

理由：这篇论文专注于评估多模态大型语言模型（MLLMs）在空间理解和序列推理任务中的表现，探讨了现有模型在这些核心能力上的不足，并提出了改进的必要性。因此，它属于LLM应用类别。` `机器人` `自动化`

> LEGO-Puzzles: How Good Are MLLMs at Multi-Step Spatial Reasoning?

# 摘要

> 多步骤空间推理需要理解并推理多个连续步骤中的空间关系，这对于机器人操作、自主导航和自动化装配等复杂现实应用至关重要。为了评估当前多模态大型语言模型（MLLMs）在这一核心能力上的表现，我们推出了	extbf{LEGO-Puzzles}——一个通过乐高任务评估MLLMs在	extbf{空间理解}和	extbf{序列推理}能力的可扩展基准测试。LEGO-Puzzles包含1,100个精心策划的视觉问答（VQA）样本，涵盖从基础空间理解到复杂多步骤推理的11种不同任务。基于LEGO-Puzzles，我们对最先进的MLLMs进行了全面评估，发现它们的空间推理能力存在明显不足：即使是最强大的MLLMs也只能正确回答约一半的测试案例，而人类参与者则达到了90%以上的准确率。除了VQA任务，我们还测试了MLLMs根据装配说明生成乐高图像的能力。实验结果显示，仅Gemini-2.0-Flash和GPT-4o能够有限地遵循这些指令，而其他MLLMs要么复制输入图像，要么生成完全不相关的输出。总之，LEGO-Puzzles揭示了现有MLLMs在空间理解和序列推理能力上的关键缺陷，并凸显了在多模态空间推理领域进一步发展的迫切需求。

> Multi-step spatial reasoning entails understanding and reasoning about spatial relationships across multiple sequential steps, which is crucial for tackling complex real-world applications, such as robotic manipulation, autonomous navigation, and automated assembly. To assess how well current Multimodal Large Language Models (MLLMs) have acquired this fundamental capability, we introduce \textbf{LEGO-Puzzles}, a scalable benchmark designed to evaluate both \textbf{spatial understanding} and \textbf{sequential reasoning} in MLLMs through LEGO-based tasks. LEGO-Puzzles consists of 1,100 carefully curated visual question-answering (VQA) samples spanning 11 distinct tasks, ranging from basic spatial understanding to complex multi-step reasoning. Based on LEGO-Puzzles, we conduct a comprehensive evaluation of state-of-the-art MLLMs and uncover significant limitations in their spatial reasoning capabilities: even the most powerful MLLMs can answer only about half of the test cases, whereas human participants achieve over 90\% accuracy. In addition to VQA tasks, we evaluate MLLMs' abilities to generate LEGO images following assembly illustrations. Our experiments show that only Gemini-2.0-Flash and GPT-4o exhibit a limited ability to follow these instructions, while other MLLMs either replicate the input image or generate completely irrelevant outputs. Overall, LEGO-Puzzles exposes critical deficiencies in existing MLLMs' spatial understanding and sequential reasoning capabilities, and underscores the need for further advancements in multimodal spatial reasoning.

[Arxiv](https://arxiv.org/abs/2503.19990)