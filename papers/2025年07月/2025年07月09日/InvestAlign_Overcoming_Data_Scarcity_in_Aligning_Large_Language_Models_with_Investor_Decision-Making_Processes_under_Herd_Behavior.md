# InvestAlign: 解决从众行为下大型语言模型与投资者决策过程对齐中的数据稀缺性挑战

发布时间：2025年07月09日

`LLM应用` `投资决策`

> InvestAlign: Overcoming Data Scarcity in Aligning Large Language Models with Investor Decision-Making Processes under Herd Behavior

# 摘要

> 在行为金融学中，将大型语言模型（LLMs）与投资者的羊群行为决策过程对齐是一个关键挑战。这一领域面临一个核心难题：用于监督微调（SFT）的真实用户数据极度匮乏。虽然SFT能够连接LLMs的输出与人类行为模式，但其对海量真实数据的依赖导致了高昂的收集成本和隐私风险。我们提出了一种名为InvestAlign的新框架，通过利用简单最优投资问题的理论解决方案，而非复杂场景，来构建高质量的SFT数据集。理论分析表明，使用InvestAlign生成的数据训练LLMs，其参数收敛速度比使用真实用户数据更快，展现出更高的学习效率。此外，我们开发了InvestAgent，这是一个经过InvestAlign微调的LLM代理。在简单和复杂投资问题中，它与真实用户数据的对齐程度远超SFT前的模型。这凸显了InvestAlign作为解决复杂最优投资问题并实现LLMs与投资者羊群行为决策过程对齐的潜力。我们的代码已公开发布在https://github.com/thu-social-network-research-group/InvestAlign。

> Aligning Large Language Models (LLMs) with investor decision-making processes under herd behavior is a critical challenge in behavioral finance, which grapples with a fundamental limitation: the scarcity of real-user data needed for Supervised Fine-Tuning (SFT). While SFT can bridge the gap between LLM outputs and human behavioral patterns, its reliance on massive authentic data imposes substantial collection costs and privacy risks. We propose InvestAlign, a novel framework that constructs high-quality SFT datasets by leveraging theoretical solutions to similar and simple optimal investment problems rather than complex scenarios. Our theoretical analysis demonstrates that training LLMs with InvestAlign-generated data achieves faster parameter convergence than using real-user data, suggesting superior learning efficiency. Furthermore, we develop InvestAgent, an LLM agent fine-tuned with InvestAlign, which demonstrates significantly closer alignment to real-user data than pre-SFT models in both simple and complex investment problems. This highlights our proposed InvestAlign as a promising approach with the potential to address complex optimal investment problems and align LLMs with investor decision-making processes under herd behavior. Our code is publicly available at https://github.com/thu-social-network-research-group/InvestAlign.

[Arxiv](https://arxiv.org/abs/2507.06528)