# InfoBid：研究基于大型语言模型的智能体在拍卖中信息披露的仿真框架

发布时间：2025年03月26日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）作为代理，在多代理拍卖场景中模拟广告商的行为，研究信息披露对市场结果的影响。通过构建仿真框架InfoBid，论文展示了LLMs在市场设计和信息策略研究中的应用，属于LLM的应用领域。` `市场设计`

> InfoBid: A Simulation Framework for Studying Information Disclosure in Auctions with Large Language Model-based Agents

# 摘要

> 在在线广告系统中，发布者常在信息披露策略上面临两难选择：更多信息虽能优化广告分配，提升效率，却可能因降低竞争广告商的不确定性而损失收入。与市场设计中的其他挑战相似，受限于现实数据获取，研究者和从业者转而依赖仿真框架。大型语言模型（LLMs）的兴起为仿真开辟了新途径，无需预设代理行为模型，即可实现类人推理与适应。尽管潜力巨大，现有框架尚未整合LLM代理研究信息不对称与信号策略，尤其在拍卖场景下。为此，我们推出了InfoBid——一个灵活的仿真框架，借助LLM代理探究多代理拍卖中的信息披露影响。基于GPT-4o，我们实现了涵盖多种信息模式的第二价格拍卖仿真。结果显示，信号对战略行为及拍卖结果的影响与经济和社会学习理论高度契合。借助InfoBid，我们旨在推动LLMs作为人类经济与社会代理的代理在实证研究中的应用，深化对其能力与局限的理解。此研究架起理论市场设计与实际应用的桥梁，助力市场仿真、信息设计与基于代理推理的研究，同时为探索数字经济动态提供有力工具。


> In online advertising systems, publishers often face a trade-off in information disclosure strategies: while disclosing more information can enhance efficiency by enabling optimal allocation of ad impressions, it may lose revenue potential by decreasing uncertainty among competing advertisers. Similar to other challenges in market design, understanding this trade-off is constrained by limited access to real-world data, leading researchers and practitioners to turn to simulation frameworks. The recent emergence of large language models (LLMs) offers a novel approach to simulations, providing human-like reasoning and adaptability without necessarily relying on explicit assumptions about agent behavior modeling. Despite their potential, existing frameworks have yet to integrate LLM-based agents for studying information asymmetry and signaling strategies, particularly in the context of auctions. To address this gap, we introduce InfoBid, a flexible simulation framework that leverages LLM agents to examine the effects of information disclosure strategies in multi-agent auction settings. Using GPT-4o, we implemented simulations of second-price auctions with diverse information schemas. The results reveal key insights into how signaling influences strategic behavior and auction outcomes, which align with both economic and social learning theories. Through InfoBid, we hope to foster the use of LLMs as proxies for human economic and social agents in empirical studies, enhancing our understanding of their capabilities and limitations. This work bridges the gap between theoretical market designs and practical applications, advancing research in market simulations, information design, and agent-based reasoning while offering a valuable tool for exploring the dynamics of digital economies.

[Arxiv](https://arxiv.org/abs/2503.22726)