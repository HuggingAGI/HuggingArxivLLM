# # 合成实验室启示录：语言模型化身拍卖参与者

发布时间：2025年07月11日

`LLM应用` `市场机制`

> Learning from Synthetic Labs: Language Models as Auction Participants

# 摘要

> 本文探讨了模拟AI代理（大型语言模型，LLMs）在拍卖中的行为表现，并提出了一种新颖的合成数据生成方法，以助力拍卖机制的研究与设计。研究发现，当LLMs具备链式思维推理能力时，其在各类经典拍卖格式中的表现与现有实验文献高度一致。具体而言，我们发现：LLM竞拍者的行为模式与风险规避的人类竞拍者相似；在明显策略稳健的拍卖中，它们的表现更接近理论预测；而在共同价值设置下，LLMs也会遭遇胜者诅咒。在提示工程方面，我们发现LLMs对简单的提示调整（如语言或货币单位的改变）并不敏感，但通过采用正确的思维模型（即基于纳什偏差的语言）可以显著改进，使其更接近理论预测。此外，我们仅花费不到400美元，便使用GPT-4模型完成了1,000多次拍卖实验（成本仅为传统拍卖实验的千分之一），并开发了一个灵活的框架，支持与任何LLM模型配合使用，并兼容多种拍卖设计规范。这一成果不仅降低了拍卖实验的成本，还为使用LLM代理作为研究工具提供了有力的证明，为未来研究开辟了新的可能性。

> This paper investigates the behavior of simulated AI agents (large language models, or LLMs) in auctions, introducing a novel synthetic data-generating process to help facilitate the study and design of auctions. We find that LLMs -- when endowed with chain of thought reasoning capacity -- agree with the experimental literature in auctions across a variety of classic auction formats. In particular, we find that LLM bidders produce results consistent with risk-averse human bidders; that they perform closer to theoretical predictions in obviously strategy-proof auctions; and, that they succumb to the winner's curse in common value settings. On prompting, we find that LLMs are not very sensitive to naive changes in prompts (e.g., language, currency) but can improve dramatically towards theoretical predictions with the right mental model (i.e., the language of Nash deviations). We run 1,000$+$ auctions for less than $\$$400 with GPT-4 models (three orders of magnitude cheaper than modern auction experiments) and develop a framework flexible enough to run auction experiments with any LLM model and a wide range of auction design specifications, facilitating further experimental study by decreasing costs and serving as a proof-of-concept for the use of LLM proxies.

[Arxiv](https://arxiv.org/abs/2507.09083)