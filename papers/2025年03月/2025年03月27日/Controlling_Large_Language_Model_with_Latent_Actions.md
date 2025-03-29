# # 利用潜在动作调控大型语言模型
探索通过潜在动作实现对大型语言模型的精准控制。

发布时间：2025年03月27日

`LLM应用`

> Controlling Large Language Model with Latent Actions

# 摘要

> 使用强化学习（RL）调整大型语言模型（LLMs）以适应下游任务已被证明是一种有效的方法。然而，LLMs本身并未定义用于RL训练的代理结构，特别是在定义动作空间方面。本文研究了学习紧凑的潜在动作空间以增强RL在LLMs中的可控性和探索性。我们提出了基于潜在动作的大型语言模型控制（CoLA），这是一个将潜在动作空间整合到预训练LLMs中的框架。我们将CoLA应用于Llama-3.1-8B模型。实验表明，与基于token级别的动作的RL相比，CoLA的潜在动作在文本生成中实现了更大的语义多样性。在增强下游任务方面，我们发现CoLA结合RL在math500基准测试中取得了42.4的分数，超过了基线分数38.2，并在结合蒙特卡洛树搜索变体后达到了68.2。此外，与基线不同，CoLA结合RL在不降低预训练LLM能力的情况下，始终提高了基于代理的任务性能。最后，CoLA将涉及通过RL增强的思考提示的任务的计算时间减少了一半。这些结果突显了CoLA在推动基于RL的LLMs下游应用适应方面的潜力。

> Adapting Large Language Models (LLMs) to downstream tasks using Reinforcement Learning (RL) has proven to be an effective approach. However, LLMs do not inherently define the structure of an agent for RL training, particularly in terms of defining the action space. This paper studies learning a compact latent action space to enhance the controllability and exploration of RL for LLMs. We propose Controlling Large Language Models with Latent Actions (CoLA), a framework that integrates a latent action space into pre-trained LLMs. We apply CoLA to the Llama-3.1-8B model. Our experiments demonstrate that, compared to RL with token-level actions, CoLA's latent action enables greater semantic diversity in text generation. For enhancing downstream tasks, we show that CoLA with RL achieves a score of 42.4 on the math500 benchmark, surpassing the baseline score of 38.2, and reaches 68.2 when augmented with a Monte Carlo Tree Search variant. Furthermore, CoLA with RL consistently improves performance on agent-based tasks without degrading the pre-trained LLM's capabilities, unlike the baseline. Finally, CoLA reduces computation time by half in tasks involving enhanced thinking prompts for LLMs by RL. These results highlight CoLA's potential to advance RL-based adaptation of LLMs for downstream applications.

[Arxiv](https://arxiv.org/abs/2503.21383)