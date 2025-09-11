# HumanAgencyBench：AI助手人类能动性支持的规模化评估

发布时间：2025年09月10日

`LLM应用` `基础理论`

> HumanAgencyBench: Scalable Evaluation of Human Agency Support in AI Assistants

# 摘要

> 当人类把越来越多的任务和决策交给人工智能（AI）时，我们正面临失去对个人及集体未来掌控的风险。相对简单的算法系统早已在左右人类决策——比如社交媒体的推送算法，会让人们不自觉地、心不在焉地刷着那些为提升互动度而优化的内容。本文中，我们融合哲学与科学的能动性理论和AI辅助评估方法，提出了人类能动性的概念——具体而言，就是利用大型语言模型（LLMs）模拟并验证用户查询，同时评估AI的响应。我们还开发了HumanAgencyBench（HAB）——一个基于典型AI应用场景、涵盖人类能动性六个维度的可扩展自适应基准。HAB用于评估AI助手或智能体在六个方面的表现倾向：主动提问澄清、拒绝价值操纵、纠正错误信息、推迟重要决策、鼓励学习新知，以及坚守社交边界。研究发现，当前基于LLM的助手对能动性的支持普遍处于中低水平，且不同开发者的系统、不同维度间的表现差异显著。比如，Anthropic的LLMs虽然整体上最支持人类能动性，但在“拒绝价值操纵”这一维度上，其支持度却是最低的。此外，能动性支持似乎并非由LLM能力的提升或指令遵循行为（如RLHF）直接带来，因此我们呼吁将目标转向更稳健的安全性与对齐性。

> As humans delegate more tasks and decisions to artificial intelligence (AI), we risk losing control of our individual and collective futures. Relatively simple algorithmic systems already steer human decision-making, such as social media feed algorithms that lead people to unintentionally and absent-mindedly scroll through engagement-optimized content. In this paper, we develop the idea of human agency by integrating philosophical and scientific theories of agency with AI-assisted evaluation methods: using large language models (LLMs) to simulate and validate user queries and to evaluate AI responses. We develop HumanAgencyBench (HAB), a scalable and adaptive benchmark with six dimensions of human agency based on typical AI use cases. HAB measures the tendency of an AI assistant or agent to Ask Clarifying Questions, Avoid Value Manipulation, Correct Misinformation, Defer Important Decisions, Encourage Learning, and Maintain Social Boundaries. We find low-to-moderate agency support in contemporary LLM-based assistants and substantial variation across system developers and dimensions. For example, while Anthropic LLMs most support human agency overall, they are the least supportive LLMs in terms of Avoid Value Manipulation. Agency support does not appear to consistently result from increasing LLM capabilities or instruction-following behavior (e.g., RLHF), and we encourage a shift towards more robust safety and alignment targets.

[Arxiv](https://arxiv.org/abs/2509.08494)