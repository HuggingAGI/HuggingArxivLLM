# 通过大型语言模型的奖励分解，实现对话代理与全局反馈的精准对齐

发布时间：2025年05月21日

`LLM应用` `对话系统`

> Aligning Dialogue Agents with Global Feedback via Large Language Model Reward Decomposition

# 摘要

> 我们提出了一种基于大型语言模型的奖励分解框架，用于仅使用单一的会话级反馈信号对齐对话代理。我们利用冻结的、预训练的大型语言模型（LLM）的推理能力，通过分解全局的、会话级的反馈来推断细粒度的局部隐含奖励。第一个仅文本的变体提示LLM仅使用对话记录进行奖励分解。第二个多模态变体结合了额外的行为线索，例如音调、 gaze 和面部情感，以自然语言描述的形式表达。这些推断出的每轮奖励被蒸馏到一个轻量级的奖励模型中，我们利用它进行基于强化学习的对话生成微调。我们对仅文本和多模态变体进行了与最新奖励分解方法的对比评估，并在人类对对话质量的评估中展示了显著改进，表明LLMs是强大的奖励分解器，无需手动奖励塑造和细粒度的人类反馈。

> We propose a large language model based reward decomposition framework for aligning dialogue agents using only a single session-level feedback signal. We leverage the reasoning capabilities of a frozen, pretrained large language model (LLM) to infer fine-grained local implicit rewards by decomposing global, session-level feedback. Our first text-only variant prompts the LLM to perform reward decomposition using only the dialogue transcript. The second multimodal variant incorporates additional behavioral cues, such as pitch, gaze, and facial affect, expressed as natural language descriptions. These inferred turn-level rewards are distilled into a lightweight reward model, which we utilize for RL-based fine-tuning for dialogue generation. We evaluate both text-only and multimodal variants against state-of-the-art reward decomposition methods and demonstrate notable improvements in human evaluations of conversation quality, suggesting that LLMs are strong reward decomposers that obviate the need for manual reward shaping and granular human feedback.

[Arxiv](https://arxiv.org/abs/2505.15922)