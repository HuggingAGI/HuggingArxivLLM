# AgentA/B：通过交互式LLM代理实现自动化且可扩展的Web A/B测试

发布时间：2025年04月13日

`LLM应用

摘要中提到，AgentA/B是一个基于大型语言模型的自主代理系统，用于模拟用户与真实网页的交互行为。该系统应用了LLM来实现用户行为模拟，属于LLM的应用层面。因此，这篇论文应归类为LLM应用。` `Web应用`

> AgentA/B: Automated and Scalable Web A/BTesting with Interactive LLM Agents

# 摘要

> A/B测试是现代Web应用中评估UI/UX设计决策的常用方法。然而，传统A/B测试受限于对大规模实时流量和漫长的测试周期的依赖。通过对六位行业专家的深入访谈，我们发现当前A/B测试流程中的主要瓶颈。为此，我们开发了AgentA/B，一个基于大型语言模型的自主代理系统，能够自动模拟用户与真实网页的交互行为。AgentA/B支持部署多样化人格的LLM代理，每个代理都能在网页上执行搜索、点击、筛选和购买等多步骤操作。在一项演示性实验中，我们使用AgentA/B模拟了针对亚马逊网站的1,000个LLM代理的间组A/B测试，并在大规模范围内将代理行为与真实人类购物行为进行对比。实验结果表明，AgentA/B能够有效模拟人类行为模式。


> A/B testing experiment is a widely adopted method for evaluating UI/UX design decisions in modern web applications. Yet, traditional A/B testing remains constrained by its dependence on the large-scale and live traffic of human participants, and the long time of waiting for the testing result. Through formative interviews with six experienced industry practitioners, we identified critical bottlenecks in current A/B testing workflows. In response, we present AgentA/B, a novel system that leverages Large Language Model-based autonomous agents (LLM Agents) to automatically simulate user interaction behaviors with real webpages. AgentA/B enables scalable deployment of LLM agents with diverse personas, each capable of navigating the dynamic webpage and interactively executing multi-step interactions like search, clicking, filtering, and purchasing. In a demonstrative controlled experiment, we employ AgentA/B to simulate a between-subject A/B testing with 1,000 LLM agents Amazon.com, and compare agent behaviors with real human shopping behaviors at a scale. Our findings suggest AgentA/B can emulate human-like behavior patterns.

[Arxiv](https://arxiv.org/abs/2504.09723)