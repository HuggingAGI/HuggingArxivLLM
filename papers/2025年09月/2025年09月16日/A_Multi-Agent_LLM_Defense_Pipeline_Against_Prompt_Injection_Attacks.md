# 一种抵御提示注入攻击的多智能体LLM防御管道

发布时间：2025年09月16日

`Agent` `基础理论`

> A Multi-Agent LLM Defense Pipeline Against Prompt Injection Attacks

# 摘要

> 提示词注入攻击是大型语言模型（LLM）部署中的重大安全隐患，攻击者可在用户输入中植入恶意指令，从而覆盖系统提示并诱导模型产生非预期行为。本文提出了一种全新的多智能体防御框架，该框架通过在协调管道中部署专门的LLM智能体，实时检测并中和提示词注入攻击。我们通过两种架构评估了该方法：顺序智能体链管道与基于分层协调器的系统。我们对55种独特的提示词注入攻击展开了全面测试——这些攻击分为8类，在ChatGLM和Llama2两个LLM平台上共生成400个攻击实例，结果显示安全性得到显著提升。在未部署防御机制时，基线攻击成功率（ASR）在ChatGLM上高达30%，在Llama2上为20%；而我们的多智能体管道实现了100%的防御效果，在所有测试场景中均将ASR降至0%。该框架在直接覆盖、代码执行尝试、数据泄露、混淆技术等多种攻击类别中展现出强大的稳健性，同时确保合法查询的系统功能不受影响。

> Prompt injection attacks represent a major vulnerability in Large Language Model (LLM) deployments, where malicious instructions embedded in user inputs can override system prompts and induce unintended behaviors. This paper presents a novel multi-agent defense framework that employs specialized LLM agents in coordinated pipelines to detect and neutralize prompt injection attacks in real-time. We evaluate our approach using two distinct architectures: a sequential chain-of-agents pipeline and a hierarchical coordinator-based system. Our comprehensive evaluation on 55 unique prompt injection attacks, grouped into 8 categories and totaling 400 attack instances across two LLM platforms (ChatGLM and Llama2), demonstrates significant security improvements. Without defense mechanisms, baseline Attack Success Rates (ASR) reached 30% for ChatGLM and 20% for Llama2. Our multi-agent pipeline achieved 100% mitigation, reducing ASR to 0% across all tested scenarios. The framework demonstrates robustness across multiple attack categories including direct overrides, code execution attempts, data exfiltration, and obfuscation techniques, while maintaining system functionality for legitimate queries.

[Arxiv](https://arxiv.org/abs/2509.14285)