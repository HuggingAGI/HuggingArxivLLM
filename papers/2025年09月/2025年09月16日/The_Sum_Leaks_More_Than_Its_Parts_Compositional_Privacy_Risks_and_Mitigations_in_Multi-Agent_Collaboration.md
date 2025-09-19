# 整体泄露大于部分之和：多智能体协作中的组合隐私风险与缓解策略

发布时间：2025年09月16日

`Agent` `基础理论`

> The Sum Leaks More Than Its Parts: Compositional Privacy Risks and Mitigations in Multi-Agent Collaboration

# 摘要

> 随着大型语言模型（LLMs）深度融入多智能体系统，新的隐私风险应运而生，这些风险已不再局限于记忆、直接推理或单轮评估。尤其是，看似无害的响应在多轮交互中组合后，可能会累积起来让攻击者得以恢复敏感信息——我们将这种现象称为组合式隐私泄露。我们首次系统性研究了多智能体LLM系统中的此类组合式隐私泄露及潜在缓解方法。首先，我们构建了一个框架，模拟辅助知识与智能体交互如何共同加剧隐私风险，即便每个单独的响应本身都是良性的。为缓解这一问题，我们提出并评估了两种防御策略：（1）心理理论防御（ToM），即防御者智能体通过预判自身输出可能被攻击者利用的方式来推断提问者意图；（2）协作共识防御（CoDef），即响应者智能体与基于共享聚合状态投票的同伴协作，从而限制敏感信息传播。重要的是，我们在评估时平衡了泄露敏感信息的组合与产生良性推断的组合。实验量化了这些防御策略在平衡隐私-效用权衡上的差异：仅依靠思维链对泄露的防护效果有限（敏感信息阻断率约39%），而ToM防御显著提升了敏感查询阻断率（高达97%），但可能降低良性任务成功率；CoDef则实现了最佳平衡，取得了最高的平衡结果（79.8%），凸显了将显式推理与防御者协作相结合的优势。总之，我们的研究揭示了协作式LLM部署中的一类新风险，并为设计抵御组合式、上下文驱动隐私泄露的防护措施提供了切实可行的见解。

> As large language models (LLMs) become integral to multi-agent systems, new privacy risks emerge that extend beyond memorization, direct inference, or single-turn evaluations. In particular, seemingly innocuous responses, when composed across interactions, can cumulatively enable adversaries to recover sensitive information, a phenomenon we term compositional privacy leakage. We present the first systematic study of such compositional privacy leaks and possible mitigation methods in multi-agent LLM systems. First, we develop a framework that models how auxiliary knowledge and agent interactions jointly amplify privacy risks, even when each response is benign in isolation. Next, to mitigate this, we propose and evaluate two defense strategies: (1) Theory-of-Mind defense (ToM), where defender agents infer a questioner's intent by anticipating how their outputs may be exploited by adversaries, and (2) Collaborative Consensus Defense (CoDef), where responder agents collaborate with peers who vote based on a shared aggregated state to restrict sensitive information spread. Crucially, we balance our evaluation across compositions that expose sensitive information and compositions that yield benign inferences. Our experiments quantify how these defense strategies differ in balancing the privacy-utility trade-off. We find that while chain-of-thought alone offers limited protection to leakage (~39% sensitive blocking rate), our ToM defense substantially improves sensitive query blocking (up to 97%) but can reduce benign task success. CoDef achieves the best balance, yielding the highest Balanced Outcome (79.8%), highlighting the benefit of combining explicit reasoning with defender collaboration. Together, our results expose a new class of risks in collaborative LLM deployments and provide actionable insights for designing safeguards against compositional, context-driven privacy leakage.

[Arxiv](https://arxiv.org/abs/2509.14284)