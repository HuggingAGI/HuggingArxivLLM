# # 基于大型语言模型的智能体行动劫持研究

发布时间：2024年12月14日

`其他

由于论文摘要翻译失败，无法准确判断其内容，因此将其归类为其他。` `知识图谱`

> Towards Action Hijacking of Large Language Model-based Agent

# 摘要

> <翻译失败>

> In the past few years, intelligent agents powered by large language models (LLMs) have achieved remarkable progress in performing complex tasks. These LLM-based agents receive queries as tasks and decompose them into various subtasks via the equipped LLMs to guide the action of external entities (\eg{}, tools, AI-agents) to answer the questions from users. Empowered by their exceptional capabilities of understanding and problem-solving, they are widely adopted in labor-intensive sectors including healthcare, finance, code completion, \etc{} At the same time, there are also concerns about the potential misuse of these agents, prompting the built-in safety guards from service providers. To circumvent the built-in guidelines, the prior studies proposed a multitude of attacks including memory poisoning, jailbreak, and prompt injection. These studies often fail to maintain effectiveness across safety filters employed by agents due to the restricted privileges and the harmful semantics in queries. In this paper, we introduce \Name, a novel hijacking attack to manipulate the action plans of black-box agent system. \Name first collects the action-aware memory through prompt theft from long-term memory. It then leverages the internal memory retrieval mechanism of the agent to provide an erroneous context. The huge gap between the latent spaces of the retriever and safety filters allows our method to bypass the detection easily. Extensive experimental results demonstrate the effectiveness of our apporach (\eg{}, 99.67\% ASR). Besides, our approach achieved an average bypass rate of 92.7\% for safety filters.

[Arxiv](https://arxiv.org/abs/2412.10807)