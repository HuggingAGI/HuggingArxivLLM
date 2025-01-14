# 逻辑与魔法的碰撞：LLMs 破解智能合约漏洞

发布时间：2025年01月12日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来检测智能合约漏洞，特别是在Solidity v0.8版本中的应用。论文通过实验展示了LLMs在降低误报率和检测特定漏洞方面的表现，属于LLM在实际应用中的具体案例，因此分类为LLM应用。` `区块链` `智能合约`

> Logic Meets Magic: LLMs Cracking Smart Contract Vulnerabilities

# 摘要

> 智能合约漏洞在区块链应用中引发了巨大的经济损失。大型语言模型（LLMs）为解决这一耗时任务带来了新的希望。然而，当前最先进的基于LLM的检测方案往往面临高误报率的挑战。
    本文在两个方面突破了现有研究的局限。首先，我们的评估基于Solidity v0.8，相比之前专注于旧版本（v0.4）的研究，提供了最新的洞见。其次，我们采用了最新的五种LLM模型（跨公司），全面覆盖了该领域的最先进能力。
    我们进行了一系列严格的实验。结果表明，精心设计的提示可以将误报率降低60%以上。令人意外的是，我们还发现，与早期版本（v0.4）相比，检测Solidity v0.8中某些特定漏洞的召回率已降至仅13%。进一步分析表明，这一下降的根源在于LLM在检测过程中过度依赖新引入库和框架的变化。

> Smart contract vulnerabilities caused significant economic losses in blockchain applications. Large Language Models (LLMs) provide new possibilities for addressing this time-consuming task. However, state-of-the-art LLM-based detection solutions are often plagued by high false-positive rates.
  In this paper, we push the boundaries of existing research in two key ways. First, our evaluation is based on Solidity v0.8, offering the most up-to-date insights compared to prior studies that focus on older versions (v0.4). Second, we leverage the latest five LLM models (across companies), ensuring comprehensive coverage across the most advanced capabilities in the field.
  We conducted a series of rigorous evaluations. Our experiments demonstrate that a well-designed prompt can reduce the false-positive rate by over 60%. Surprisingly, we also discovered that the recall rate for detecting some specific vulnerabilities in Solidity v0.8 has dropped to just 13% compared to earlier versions (i.e., v0.4). Further analysis reveals the root cause of this decline: the reliance of LLMs on identifying changes in newly introduced libraries and frameworks during detection.

[Arxiv](https://arxiv.org/abs/2501.07058)