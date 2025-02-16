# 过度思考：针对推理型LLM的减速攻击

发布时间：2025年02月05日

`LLM应用` `网络安全` `人工智能`

> OverThink: Slowdown Attacks on Reasoning LLMs

# 摘要

> 我们增加了依赖推理的大型语言模型（LLMs）的应用开销——迫使模型消耗更多推理令牌，即“过思考”，以便在提供上下文正确答案的同时响应用户的查询。攻击者通过在推理过程中向用于推理的公共内容（例如用于RAG应用的推理LLM）中注入诱饵推理问题，执行OVERTHINK攻击。由于我们诱饵问题的性质（例如马尔可夫决策过程），修改后的文本不会违反安全护栏。我们在闭源（OpenAI o1, o1-mini, o3-mini）和开源（DeepSeek R1）推理模型上，使用FreshQA和SQuAD数据集评估了我们的攻击。结果显示，在FreshQA数据集上速度减慢了18倍，在SQuAD数据集上速度减慢了46倍。该攻击还显示出在不同模型之间的高度可迁移性。为了保护应用程序，我们讨论并实现了基于LLM和系统设计方法的防御措施。最后，我们讨论了OVERTHINK攻击对社会、财务和能源的影响，这可能会增加第三方应用程序在运行推理模型时的成本。

> We increase overhead for applications that rely on reasoning LLMs-we force models to spend an amplified number of reasoning tokens, i.e., "overthink", to respond to the user query while providing contextually correct answers. The adversary performs an OVERTHINK attack by injecting decoy reasoning problems into the public content that is used by the reasoning LLM (e.g., for RAG applications) during inference time. Due to the nature of our decoy problems (e.g., a Markov Decision Process), modified texts do not violate safety guardrails. We evaluated our attack across closed-(OpenAI o1, o1-mini, o3-mini) and open-(DeepSeek R1) weights reasoning models on the FreshQA and SQuAD datasets. Our results show up to 18x slowdown on FreshQA dataset and 46x slowdown on SQuAD dataset. The attack also shows high transferability across models. To protect applications, we discuss and implement defenses leveraging LLM-based and system design approaches. Finally, we discuss societal, financial, and energy impacts of OVERTHINK attack which could amplify the costs for third-party applications operating reasoning models.

[Arxiv](https://arxiv.org/abs/2502.02542)