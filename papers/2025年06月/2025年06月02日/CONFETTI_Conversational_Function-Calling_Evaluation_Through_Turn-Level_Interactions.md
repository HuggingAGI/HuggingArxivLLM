# # CONFETTI：基于回合交互的对话式功能调用评估

发布时间：2025年06月02日

`LLM应用` `对话系统`

> CONFETTI: Conversational Function-Calling Evaluation Through Turn-Level Interactions

# 摘要

> 我们推出了通过轮次交互进行对话式功能调用评估的基准——CONFETTI（Conversational Function-Calling Evaluation Through Turn-Level Interactions），这是一个专为评估大型语言模型（LLMs）的功能调用能力和回复质量而设计的对话基准。当前的基准在评估LLMs在复杂对话场景下的表现方面存在不足。CONFETTI通过109个模拟人类对话、包含313个用户轮次以及覆盖86个API来填补这一空白。这些对话明确针对各种对话复杂性，如后续对话、目标修正和切换、模糊和隐含目标等。我们使用此基准进行针对功能调用的离策略轮次评估。我们的基准还纳入了对话行为标注，以评估代理回复。我们评估了一系列最先进的LLMs，并分析了它们在可用API数量、对话长度和链式功能调用方面的表现。我们的结果显示，尽管某些模型能够处理长对话，并成功利用20多个API，但其他模型在处理更长上下文或增加API数量时却显得力不从心。我们还发现，所有模型在链式功能调用上的表现都受到严重限制。总体而言，在CONFETTI中表现最佳的模型是Nova Pro（40.01%）、Claude Sonnet v3.5（35.46%）和Llama 3.1 405B（33.19%），紧随其后的是command-r-plus（31.18%）和Mistral-Large-2407（30.07%）。

> We introduce Conversational Function-Calling Evaluation Through Turn-Level Interactions (CONFETTI), a conversational benchmark1 designed to evaluate the function-calling capabilities and response quality of large language models (LLMs). Current benchmarks lack comprehensive assessment of LLMs in complex conversational scenarios. CONFETTI addresses this gap through 109 human-simulated conversations, comprising 313 user turns and covering 86 APIs. These conversations explicitly target various conversational complexities, such as follow-ups, goal correction and switching, ambiguous and implicit goals. We perform off-policy turn-level evaluation using this benchmark targeting function-calling. Our benchmark also incorporates dialog act annotations to assess agent responses. We evaluate a series of state-of-the-art LLMs and analyze their performance with respect to the number of available APIs, conversation lengths, and chained function calling. Our results reveal that while some models are able to handle long conversations, and leverage more than 20+ APIs successfully, other models struggle with longer context or when increasing the number of APIs. We also report that the performance on chained function-calls is severely limited across the models. Overall, the top performing models on CONFETTI are Nova Pro (40.01%), Claude Sonnet v3.5 (35.46%) and Llama 3.1 405B (33.19%) followed by command-r-plus (31.18%) and Mistral-Large-2407 (30.07%).

[Arxiv](https://arxiv.org/abs/2506.01859)