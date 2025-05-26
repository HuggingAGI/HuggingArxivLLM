# CRAKEN：具备基于知识的执行能力的网络安全大语言模型代理。

发布时间：2025年05月21日

`Agent` `网络安全` `知识图谱`

> CRAKEN: Cybersecurity LLM Agent with Knowledge-Based Execution

# 摘要

> 大型语言模型（LLM）代理能够自动化网络安全任务，并且无需重新设计系统就能适应不断变化的网络安全环境。尽管LLM代理在夺旗赛（CTF）竞赛中展现了网络安全能力，但它们存在两个关键限制：无法访问超出训练数据范围的最新网络安全专业知识，以及难以将新知识整合到复杂任务规划中。将技术理解融入任务解决自动化的知识型方法可以解决这些问题。我们提出了一种名为CRAKEN的知识型LLM代理框架，该框架通过三种核心机制提升网络安全能力：任务关键信息的上下文分解、迭代自我反思的知识检索，以及将见解转化为适应性攻击策略的知识提示注入。通过不同配置的全面评估表明，与之前的方法相比，CRAKEN在多阶段漏洞检测和利用方面表现出色。我们的可扩展架构为将新安全知识嵌入到LLM驱动的网络安全代理系统中建立了新的方法论。借助一个包含CTF竞赛解题思路的知识库，CRAKEN在NYU CTF基准测试中达到了22%的准确率，比之前的工作高出3%，并取得了最新的研究结果。在MITRE ATT&CK技术评估中，CRAKEN解决了比之前工作多25-30%的技术，展示了通过知识型执行提升的网络安全能力。我们已将我们的框架开源，公众可访问https://github.com/NYU-LLM-CTF/nyuctf_agents_craken。

> Large Language Model (LLM) agents can automate cybersecurity tasks and can adapt to the evolving cybersecurity landscape without re-engineering. While LLM agents have demonstrated cybersecurity capabilities on Capture-The-Flag (CTF) competitions, they have two key limitations: accessing latest cybersecurity expertise beyond training data, and integrating new knowledge into complex task planning. Knowledge-based approaches that incorporate technical understanding into the task-solving automation can tackle these limitations. We present CRAKEN, a knowledge-based LLM agent framework that improves cybersecurity capability through three core mechanisms: contextual decomposition of task-critical information, iterative self-reflected knowledge retrieval, and knowledge-hint injection that transforms insights into adaptive attack strategies. Comprehensive evaluations with different configurations show CRAKEN's effectiveness in multi-stage vulnerability detection and exploitation compared to previous approaches. Our extensible architecture establishes new methodologies for embedding new security knowledge into LLM-driven cybersecurity agentic systems. With a knowledge database of CTF writeups, CRAKEN obtained an accuracy of 22% on NYU CTF Bench, outperforming prior works by 3% and achieving state-of-the-art results. On evaluation of MITRE ATT&CK techniques, CRAKEN solves 25-30% more techniques than prior work, demonstrating improved cybersecurity capabilities via knowledge-based execution. We make our framework open source to public https://github.com/NYU-LLM-CTF/nyuctf_agents_craken.

[Arxiv](https://arxiv.org/abs/2505.17107)