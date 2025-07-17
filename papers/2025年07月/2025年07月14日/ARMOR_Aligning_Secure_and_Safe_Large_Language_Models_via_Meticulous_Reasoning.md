# # ARMOR：细致推理助力安全可靠的大型语言模型对齐
ARMOR: 通过细致推理对齐安全可靠的大型语言模型

发布时间：2025年07月14日

`LLM理论` `人工智能`

> ARMOR: Aligning Secure and Safe Large Language Models via Meticulous Reasoning

# 摘要

> 大型语言模型（LLMs）虽然生成能力卓越，但其易受滥用的特性引发了重大的安全顾虑。尽管训练后安全对齐方法已被广泛应用，LLMs仍易受到能绕过安全限制的恶意指令攻击。近期研究引入了推理时安全推理（系统2对齐），即LLMs在最终回应前进行安全验证的推理过程。然而，这些验证机制依赖于非结构化的即兴推理，与人类有条理的推理过程大相径庭——人类首先识别用户的真正意图，再基于此评估相关风险。因此，这些防御措施仍易受复杂绕过攻击，这些攻击将有害目标隐藏于看似无害的语言中。

为了构建安全可靠的LLMs，我们提出了一种基于推理的安全对齐框架ARMOR，它以与人类一致的结构化推理过程取代了即兴的思维链推理。在推理阶段，ARMOR（1）识别潜在的绕过策略，（2）提取用户的核心意图同时摒弃欺骗性指令，（3）对净化后的请求应用基于政策的安全分析。ARMOR在自适应绕过攻击和多个安全基准上进行了评估，并通过测试时缩放进一步提升了性能。结果表明，ARMOR显著增强了对抗最新自适应绕过攻击的鲁棒性，并在各种安全基准上超越了近期的推理对齐模型。

> Large Language Models (LLMs) have demonstrated remarkable generative capabilities. However, their susceptibility to misuse has raised significant safety concerns. While post-training safety alignment methods have been widely adopted, LLMs remain vulnerable to malicious instructions that can bypass safety constraints. Recent efforts have introduced inference-time safety reasoning (system-2 alignment), where LLMs conduct a reasoning process to perform safety verification before final response. We show, however, that these checks are driven by ad-hoc reasoning that diverges from the structured human process, where they first discern a user's true intent, then evaluate the associated risk based on the true intent. Consequently, these defenses remain vulnerable to sophisticated jailbreak prompts that cloak harmful goals in seemingly benign language. To build secure and safe LLMs, we propose a reasoning-based safety alignment framework, ARMOR, that replaces the ad-hoc chains of thought reasoning process with human-aligned, structured one. At inference, ARMOR (1) detects likely jailbreak strategies, (2) extracts the user's core intent while discarding deceptive instructions, and (3) applies a policy-grounded safety analysis to the purified request. ARMOR is evaluated on adaptive jailbreak attacks and multiple safety benchmarks, and a test-time scaling is conducted to further improve its performance. Results demonstrate that ARMOR significantly enhances the robustness against state-of-the-art adaptive jailbreak attacks and outperforms recent reasoning-based aligned models across various safety benchmarks.

[Arxiv](https://arxiv.org/abs/2507.11500)