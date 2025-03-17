# 拓宽你的SCOPE！基于语义空间的多轮对话规划新方法

发布时间：2025年03月14日

`LLM应用` `聊天机器人` `AI助手`

> Broaden your SCOPE! Efficient Multi-turn Conversation Planning for LLMs using Semantic Space

# 摘要

> 大型语言模型（LLMs）被用于聊天机器人或AI助手，与人类用户进行对话。在这些应用场景中，对话的质量（例如用户参与度、安全性）非常重要，但只有在对话结束时才能确切得知。为了最大化对话的预期质量，对话规划通过推理对话中的随机转换来选择每一轮的最佳LLM响应。现有的基于模拟的对话规划算法通常通过在每一轮进行大量LLM查询来模拟未来对话，从而选择最佳响应。然而，这个过程极其耗时，因此对于实时对话来说并不实际。本文提出了一种名为语义空间优化对话规划（SCOPE）的新方法，该方法利用对话的密集语义表示来高效地进行对话规划。具体来说，SCOPE建模了对话语义中的随机转换及其相关奖励，完全在语义空间内进行规划。这使我们能够在每一轮对话中选择最佳的LLM响应，而无需额外的LLM查询进行模拟。因此，当应用于各种对话开头和两个现实世界中常见的奖励函数时，SCOPE的对话规划速度比传统的基于模拟的规划算法快70倍，同时在实际规划预算内实现更高的奖励。我们的代码可在以下链接找到：https://github.com/chenzhiliang94/convo-plan-SCOPE。

> Large language models (LLMs) are used in chatbots or AI assistants to hold conversations with a human user. In such applications, the quality (e.g., user engagement, safety) of a conversation is important and can only be exactly known at the end of the conversation. To maximize its expected quality, conversation planning reasons about the stochastic transitions within a conversation to select the optimal LLM response at each turn. Existing simulation-based conversation planning algorithms typically select the optimal response by simulating future conversations with a large number of LLM queries at every turn. However, this process is extremely time-consuming and hence impractical for real-time conversations. This paper presents a novel approach called Semantic space COnversation Planning with improved Efficiency (SCOPE) that exploits the dense semantic representation of conversations to perform conversation planning efficiently. In particular, SCOPE models the stochastic transitions in conversation semantics and their associated rewards to plan entirely within the semantic space. This allows us to select the optimal LLM response at every conversation turn without needing additional LLM queries for simulation. As a result, SCOPE can perform conversation planning 70 times faster than conventional simulation-based planning algorithms when applied to a wide variety of conversation starters and two reward functions seen in the real world, yet achieving a higher reward within a practical planning budget. Our code can be found at: https://github.com/chenzhiliang94/convo-plan-SCOPE.

[Arxiv](https://arxiv.org/abs/2503.11586)