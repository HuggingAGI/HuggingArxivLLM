# 基于结构化攻击树的LLM驱动渗透测试引导式推理

发布时间：2025年09月09日

`Agent` `基础理论`

> Guided Reasoning in LLM-Driven Penetration Testing Using Structured Attack Trees

# 摘要

> 大型语言模型（LLMs）的最新进展，激发了网络安全渗透测试工作流自动化的研究兴趣，有望为企业系统实现更快、更一致的漏洞评估。现有渗透测试LLM代理主要依赖自我引导推理，这可能导致流程步骤不准确甚至产生幻觉，进而使代理采取无效操作，例如攻击未使用的软件库或生成重复先前策略的循环响应。为此，本研究提出一种用于渗透测试LLM代理的引导推理管道，该管道整合了基于MITRE ATT&CK矩阵构建的确定性任务树（一种成熟的渗透测试杀伤链），将LLM的推理过程限定在明确定义的战术、技术与流程范围内。这一设计将推理锚定在成熟的渗透测试方法论中，并通过引导代理采用更高效的攻击流程，过滤掉无效操作。为验证该方法，我们基于三个LLM（Llama-3-8B、Gemini-1.5和GPT-4）构建了自动化渗透测试LLM代理，将其应用于10个HackTheBox网络安全练习（包含103个模拟真实网络攻击场景的离散子任务）。结果显示，所提推理管道分别引导Llama-3-8B、Gemini-1.5和GPT-4完成了71.8%、72.8%和78.6%的子任务；相比之下，采用自我引导推理的最先进LLM渗透测试工具仅完成13.5%、16.5%和75.7%的子任务，且所需模型查询量分别增加86.2%、118.7%和205.9%。这表明，在LLM推理管道中整合确定性任务树可有效提升自动化网络安全评估的准确性与效率。

> Recent advances in Large Language Models (LLMs) have driven interest in automating cybersecurity penetration testing workflows, offering the promise of faster and more consistent vulnerability assessment for enterprise systems. Existing LLM agents for penetration testing primarily rely on self-guided reasoning, which can produce inaccurate or hallucinated procedural steps. As a result, the LLM agent may undertake unproductive actions, such as exploiting unused software libraries or generating cyclical responses that repeat prior tactics. In this work, we propose a guided reasoning pipeline for penetration testing LLM agents that incorporates a deterministic task tree built from the MITRE ATT&CK Matrix, a proven penetration testing kll chain, to constrain the LLM's reaoning process to explicitly defined tactics, techniques, and procedures. This anchors reasoning in proven penetration testing methodologies and filters out ineffective actions by guiding the agent towards more productive attack procedures. To evaluate our approach, we built an automated penetration testing LLM agent using three LLMs (Llama-3-8B, Gemini-1.5, and GPT-4) and applied it to navigate 10 HackTheBox cybersecurity exercises with 103 discrete subtasks representing real-world cyberattack scenarios. Our proposed reasoning pipeline guided the LLM agent through 71.8\%, 72.8\%, and 78.6\% of subtasks using Llama-3-8B, Gemini-1.5, and GPT-4, respectively. Comparatively, the state-of-the-art LLM penetration testing tool using self-guided reasoning completed only 13.5\%, 16.5\%, and 75.7\% of subtasks and required 86.2\%, 118.7\%, and 205.9\% more model queries. This suggests that incorporating a deterministic task tree into LLM reasoning pipelines can enhance the accuracy and efficiency of automated cybersecurity assessments

[Arxiv](https://arxiv.org/abs/2509.07939)