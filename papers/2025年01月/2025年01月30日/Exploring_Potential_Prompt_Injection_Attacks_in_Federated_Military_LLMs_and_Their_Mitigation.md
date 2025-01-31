# 探究联邦军事LLMs中的提示注入攻击风险及其应对策略

发布时间：2025年01月30日

`LLM应用

理由：这篇论文讨论了联邦学习（FL）在军事合作中的应用，特别是用于开发大型语言模型（LLMs）并确保数据主权。论文还探讨了提示注入攻击对军事LLMs的潜在威胁，并提出了一个结合技术和政策手段的人机协作框架来应对这些风险。这些内容主要涉及LLM在实际应用中的安全性和策略，因此应归类为“LLM应用”。` `联邦学习`

> Exploring Potential Prompt Injection Attacks in Federated Military LLMs and Their Mitigation

# 摘要

> # 联邦学习（FL）在军事合作中的应用
联邦学习（FL）在军事合作中日益普及，用于开发大型语言模型（LLMs）并确保数据主权。然而，提示注入攻击——即对输入提示的恶意操纵——带来了新的威胁，可能危及操作安全、干扰决策并削弱盟友间的信任。本文指出了联邦军事LLMs的四大潜在漏洞：秘密数据泄露、搭便车行为、系统中断和错误信息传播。为应对这些风险，我们提出了一个人机协作框架，结合技术和政策手段。技术层面，通过红/蓝队对抗演练和质量保证来检测和缓解共享LLM权重的对抗行为；政策层面，推动联合人机政策制定和安全协议验证。我们的研究将为未来指明方向，并强调在新兴军事环境中的主动策略。

> Federated Learning (FL) is increasingly being adopted in military collaborations to develop Large Language Models (LLMs) while preserving data sovereignty. However, prompt injection attacks-malicious manipulations of input prompts-pose new threats that may undermine operational security, disrupt decision-making, and erode trust among allies. This perspective paper highlights four potential vulnerabilities in federated military LLMs: secret data leakage, free-rider exploitation, system disruption, and misinformation spread. To address these potential risks, we propose a human-AI collaborative framework that introduces both technical and policy countermeasures. On the technical side, our framework uses red/blue team wargaming and quality assurance to detect and mitigate adversarial behaviors of shared LLM weights. On the policy side, it promotes joint AI-human policy development and verification of security protocols. Our findings will guide future research and emphasize proactive strategies for emerging military contexts.

[Arxiv](https://arxiv.org/abs/2501.18416)