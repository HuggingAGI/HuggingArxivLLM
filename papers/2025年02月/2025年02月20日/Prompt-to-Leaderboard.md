# # 从提示到排行榜

发布时间：2025年02月20日

`LLM应用` `聊天机器人`

> Prompt-to-Leaderboard

# 摘要

> 大型语言模型（LLM）的评估通常依赖于聚合指标，如准确率或人类偏好，这些指标会在用户和提示之间进行平均。这种平均化处理掩盖了模型性能在用户和提示层面的特定差异。为了解决这一问题，我们提出了基于提示的排行榜（P2L）方法。该方法的核心思想是训练一个LLM，使其将自然语言提示作为输入，输出Bradley-Terry系数向量，然后利用这些系数向量来预测人类偏好投票。由此产生的基于提示的排行榜支持无监督的任务特定评估、将查询路由到最合适的模型、个性化设置，以及对模型优势和劣势的自动化评估。来自Chatbot Arena的数据表明，P2L比平均化的排行榜更能捕捉语言模型性能的细微差别。此外，我们的研究发现，P2L生成特定提示评估的能力遵循与大型语言模型自身相似的幂律缩放规律。基于此方法论训练的路由器在2025年1月登顶Chatbot Arena排行榜。我们的代码可在以下GitHub链接中获取：https://github.com/lmarena/p2l.

> Large language model (LLM) evaluations typically rely on aggregated metrics like accuracy or human preference, averaging across users and prompts. This averaging obscures user- and prompt-specific variations in model performance. To address this, we propose Prompt-to-Leaderboard (P2L), a method that produces leaderboards specific to a prompt. The core idea is to train an LLM taking natural language prompts as input to output a vector of Bradley-Terry coefficients which are then used to predict the human preference vote. The resulting prompt-dependent leaderboards allow for unsupervised task-specific evaluation, optimal routing of queries to models, personalization, and automated evaluation of model strengths and weaknesses. Data from Chatbot Arena suggest that P2L better captures the nuanced landscape of language model performance than the averaged leaderboard. Furthermore, our findings suggest that P2L's ability to produce prompt-specific evaluations follows a power law scaling similar to that observed in LLMs themselves. In January 2025, the router we trained based on this methodology achieved the \#1 spot in the Chatbot Arena leaderboard. Our code is available at this GitHub link: https://github.com/lmarena/p2l.

[Arxiv](https://arxiv.org/abs/2502.14855)