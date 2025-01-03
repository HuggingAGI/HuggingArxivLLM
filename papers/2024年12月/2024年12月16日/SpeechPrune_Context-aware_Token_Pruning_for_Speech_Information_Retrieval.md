# SpeechPrune: 语音信息检索中的上下文感知令牌剪枝

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要讨论了语音大语言模型（Speech LLMs）在长上下文任务中的应用，特别是通过提出一种新的令牌修剪策略（SpeechPrune）来提升模型在处理长音频时的性能。论文的核心是应用大语言模型技术来解决实际问题（语音信息检索），并提出了具体的优化方法（SpeechPrune），因此属于LLM应用类别。` `语音处理` `信息检索`

> SpeechPrune: Context-aware Token Pruning for Speech Information Retrieval

# 摘要

> 我们提出了语音信息检索（SIR），这是语音大语言模型（Speech LLMs）的一个新长上下文任务，并推出了SPIRAL基准测试，包含1,012个样本，用于评估模型从约90秒语音中提取关键信息的能力。尽管当前Speech LLMs在短任务上表现出色，但在处理长音频时面临计算和表示挑战。为此，我们提出了SpeechPrune，一种无需训练的令牌修剪策略，通过语音-文本相似性和近似注意力分数高效剔除无关令牌。在SPIRAL测试中，SpeechPrune在20%修剪率下，准确率分别比原始模型和随机修剪模型提升了29%和47%。即使在80%的高修剪率下，SpeechPrune仍能保持网络性能。这一方法展示了令牌级修剪在高效、可扩展的长语音理解中的巨大潜力。

> We introduce Speech Information Retrieval (SIR), a new long-context task for Speech Large Language Models (Speech LLMs), and present SPIRAL, a 1,012-sample benchmark testing models' ability to extract critical details from approximately 90-second spoken inputs. While current Speech LLMs excel at short-form tasks, they struggle with the computational and representational demands of longer audio sequences. To address this limitation, we propose SpeechPrune, a training-free token pruning strategy that uses speech-text similarity and approximated attention scores to efficiently discard irrelevant tokens. In SPIRAL, SpeechPrune achieves accuracy improvements of 29% and up to 47% over the original model and the random pruning model at a pruning rate of 20%, respectively. SpeechPrune can maintain network performance even at a pruning level of 80%. This approach highlights the potential of token-level pruning for efficient and scalable long-form speech understanding.

[Arxiv](https://arxiv.org/abs/2412.12009)