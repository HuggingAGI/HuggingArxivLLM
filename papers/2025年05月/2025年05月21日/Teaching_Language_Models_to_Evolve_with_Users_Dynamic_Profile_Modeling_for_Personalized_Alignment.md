# 让语言模型与用户共同进化：动态画像建模，实现个性化对齐

发布时间：2025年05月21日

`LLM应用

摘要讨论了大型语言模型（LLM）在嵌入即服务（EaaS）中的安全性，特别是多语言模型的嵌入反转攻击。这属于LLM的实际应用和安全性研究，因此归类为LLM应用。` `问答系统`

> Teaching Language Models to Evolve with Users: Dynamic Profile Modeling for Personalized Alignment

# 摘要

> <翻译失败>

> Personalized alignment is essential for enabling large language models (LLMs) to engage effectively in user-centric dialogue. While recent prompt-based and offline optimization methods offer preliminary solutions, they fall short in cold-start scenarios and long-term personalization due to their inherently static and shallow designs. In this work, we introduce the Reinforcement Learning for Personalized Alignment (RLPA) framework, in which an LLM interacts with a simulated user model to iteratively infer and refine user profiles through dialogue. The training process is guided by a dual-level reward structure: the Profile Reward encourages accurate construction of user representations, while the Response Reward incentivizes generation of responses consistent with the inferred profile. We instantiate RLPA by fine-tuning Qwen-2.5-3B-Instruct, resulting in Qwen-RLPA, which achieves state-of-the-art performance in personalized dialogue. Empirical evaluations demonstrate that Qwen-RLPA consistently outperforms prompting and offline fine-tuning baselines, and even surpasses advanced commercial models such as Claude-3.5 and GPT-4o. Further analysis highlights Qwen-RLPA's robustness in reconciling conflicting user preferences, sustaining long-term personalization and delivering more efficient inference compared to recent reasoning-focused LLMs. These results emphasize the potential of dynamic profile inference as a more effective paradigm for building personalized dialogue systems.

[Arxiv](https://arxiv.org/abs/2505.15456)