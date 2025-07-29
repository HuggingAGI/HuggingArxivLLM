# # AI代理部署的安全挑战：基于大规模公开竞赛的洞察

发布时间：2025年07月28日

`Agent`

> Security Challenges in AI Agent Deployment: Insights from a Large Scale Public Competition

# 摘要

> LLM驱动的AI代理如今能够通过结合语言模型推理、工具、记忆和网络访问，自主完成复杂任务。但这些系统在现实环境中，尤其是在面对攻击时，能否遵循部署策略？为研究这一问题，我们举办了有史以来规模最大的公开红队竞赛，针对22个前沿AI代理，在44个现实部署场景中进行测试。参与者提交了180万个注入攻击，其中6万多次成功引发了政策违规，例如未经授权的数据访问、非法财务行为和监管不合规。我们利用这些结果构建了Agent Red Teaming (ART) 基准——一套经过精选的高影响力攻击——并在19个最先进的模型上进行了评估。几乎所有代理在10-100次查询内都出现了政策违规行为，且攻击在不同模型和任务间具有高度可转移性。重要的是，我们发现代理的健壮性与模型大小、能力和推理时间计算资源之间关联性有限，这意味着需要额外的防御措施来防止对抗性滥用。我们的发现突显了当前AI代理中的关键且持续存在的漏洞。通过发布ART基准和相应的评估框架，我们旨在支持更严格的安保评估，并推动更安全的代理部署。

> Recent advances have enabled LLM-powered AI agents to autonomously execute complex tasks by combining language model reasoning with tools, memory, and web access. But can these systems be trusted to follow deployment policies in realistic environments, especially under attack? To investigate, we ran the largest public red-teaming competition to date, targeting 22 frontier AI agents across 44 realistic deployment scenarios. Participants submitted 1.8 million prompt-injection attacks, with over 60,000 successfully eliciting policy violations such as unauthorized data access, illicit financial actions, and regulatory noncompliance. We use these results to build the Agent Red Teaming (ART) benchmark - a curated set of high-impact attacks - and evaluate it across 19 state-of-the-art models. Nearly all agents exhibit policy violations for most behaviors within 10-100 queries, with high attack transferability across models and tasks. Importantly, we find limited correlation between agent robustness and model size, capability, or inference-time compute, suggesting that additional defenses are needed against adversarial misuse. Our findings highlight critical and persistent vulnerabilities in today's AI agents. By releasing the ART benchmark and accompanying evaluation framework, we aim to support more rigorous security assessment and drive progress toward safer agent deployment.

[Arxiv](https://arxiv.org/abs/2507.20526)