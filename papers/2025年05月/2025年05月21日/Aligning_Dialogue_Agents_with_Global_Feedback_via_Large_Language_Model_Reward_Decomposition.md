# 通过大型语言模型的奖励分解方法，实现对话智能体与全局反馈的高效对齐

发布时间：2025年05月21日

`Agent` `人工智能` `对话系统`

> Aligning Dialogue Agents with Global Feedback via Large Language Model Reward Decomposition

# 摘要

> 我们提出了一种基于大型语言模型的奖励分解框架，仅需单个会话级别的反馈信号即可对齐对话代理。该框架利用冻结的预训练大型语言模型（LLM）的推理能力，通过分解全局的会话级别反馈来推断精细的局部隐式奖励。具体而言，第一种仅文本的变体提示LLM仅使用对话记录来执行奖励分解，而第二种多模态变体则结合了音调、 gaze 和面部表情等行为线索，以自然语言描述的形式进行表达。这些推断出的每一轮奖励被蒸馏到一个轻量级的奖励模型中，并用于基于强化学习的对话生成微调。实验结果表明，与现有方法相比，该框架在对话质量的人类评估中表现出显著提升，证明了LLMs在奖励分解方面的强大能力，从而无需手动奖励塑造和粒度的人类反馈。

> We propose a large language model based reward decomposition framework for aligning dialogue agents using only a single session-level feedback signal. We leverage the reasoning capabilities of a frozen, pretrained large language model (LLM) to infer fine-grained local implicit rewards by decomposing global, session-level feedback. Our first text-only variant prompts the LLM to perform reward decomposition using only the dialogue transcript. The second multimodal variant incorporates additional behavioral cues, such as pitch, gaze, and facial affect, expressed as natural language descriptions. These inferred turn-level rewards are distilled into a lightweight reward model, which we utilize for RL-based fine-tuning for dialogue generation. We evaluate both text-only and multimodal variants against state-of-the-art reward decomposition methods and demonstrate notable improvements in human evaluations of conversation quality, suggesting that LLMs are strong reward decomposers that obviate the need for manual reward shaping and granular human feedback.

[Arxiv](https://arxiv.org/abs/2505.15922)