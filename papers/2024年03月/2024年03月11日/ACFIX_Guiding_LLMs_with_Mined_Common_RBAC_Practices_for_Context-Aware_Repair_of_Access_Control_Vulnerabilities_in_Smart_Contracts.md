# ACFIX方案，旨在借助挖掘出的常见RBAC实践引导大型语言模型，针对智能合约中的上下文敏感访问控制漏洞进行精准修复。

发布时间：2024年03月11日

`LLM应用`

> ACFIX: Guiding LLMs with Mined Common RBAC Practices for Context-Aware Repair of Access Control Vulnerabilities in Smart Contracts

# 摘要

> 智能合约面临多种安全隐患，而访问控制（AC）漏洞尤为致命。尽管已有多种检测工具面世，但如何在智能合约中自动化并恰当地修复这类漏洞仍然困难重重，尤其是它要求在大量非AC相关的源代码中精准识别并配置适宜的角色与权限，这近乎于人工智能级别的任务。鉴于此，我们借助大型语言模型（LLMs）领域的最新成果，采用尖端的GPT-4模型，并创新性地引入了一种名为ACFIX的方法论。核心理念是，我们从海量合约中提炼出各类主流代码功能所共有的AC实践模式，并以此为依据，指导LLMs针对具备相似功能的代码实现精准修复。ACFIX分为两步走：第一步，离线阶段，从超过34万份链上合约中抽丝剥茧，整理出一套基于角色的访问控制（RBAC）实践规范，明确了顶级1000对角色-权限关系中的49对重要组合；第二步，在线阶段，ACFIX实时追踪合约内的AC相关元素，凭借上下文信息和独特的“思维链”处理流程，指引LLMs为待修复合约找准最匹配的角色-权限对，并自动生成适用的补丁程序，之后还需经过有效性及效能检验。为了验证ACFIX的效果，我们搭建了首个包含118个实际AC漏洞的真实场景基准数据集。实验结果表明，ACFIX成功修复了其中94.92%的漏洞，相较于仅能修复52.54%漏洞的基础版GPT-4，这一成果堪称重大突破。

> Smart contracts are susceptible to various security issues, among which access control (AC) vulnerabilities are particularly critical. While existing research has proposed multiple detection tools, the automatic and appropriate repair of AC vulnerabilities in smart contracts remains a challenge. Unlike commonly supported vulnerability types by existing repair tools, such as reentrancy, which are usually fixed by template-based approaches, the main obstacle of AC lies in identifying the appropriate roles or permissions amid a long list of non-AC-related source code to generate proper patch code, a task that demands human-level intelligence.
  Leveraging recent advancements in large language models (LLMs), we employ the state-of-the-art GPT-4 model and enhance it with a novel approach called ACFIX. The key insight is that we can mine common AC practices for major categories of code functionality and use them to guide LLMs in fixing code with similar functionality. To this end, ACFIX involves both offline and online phases. First, during the offline phase, ACFIX mines a tax- onomy of common Role-based Access Control (RBAC) practices from 344,251 on-chain contracts, categorizing 49 role-permission pairs from the top 1,000 pairs mined. Second, during the online phase, ACFIX tracks AC-related elements across the contract and uses this context information along with a Chain-of-Thought pipeline to guide LLMs in identifying the most appropriate role-permission pair for the subject contract and subsequently generating a suitable patch. This patch will then undergo a validity and effectiveness check. To evaluate ACFIX, we built the first benchmark dataset of 118 real-world AC vulnerabilities, and our evaluation revealed that ACFIX successfully repaired 94.92% of them. This represents a significant improvement compared to the baseline GPT-4, which achieved only 52.54%.

[Arxiv](https://arxiv.org/abs/2403.06838)