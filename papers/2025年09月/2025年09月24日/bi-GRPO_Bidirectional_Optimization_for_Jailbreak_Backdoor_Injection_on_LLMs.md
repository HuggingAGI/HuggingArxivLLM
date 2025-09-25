# bi-GRPO：针对大型语言模型（LLMs）越狱后门注入的双向优化

发布时间：2025年09月24日

`强化学习` `基础理论`

> bi-GRPO: Bidirectional Optimization for Jailbreak Backdoor Injection on LLMs

# 摘要

> 随着大型语言模型（LLMs）的飞速发展，其抵御对抗性操纵（尤其是越狱后门攻击）的鲁棒性已成为关键问题。现有的嵌入越狱触发器方法（如监督微调（SFT）、模型编辑和人类反馈强化学习（RLHF））均存在局限，例如泛化能力弱、隐蔽性不足，或生成的越狱响应上下文可用性下降。为解决这些问题，我们提出bi-GRPO（双向组相对策略优化）——一种专为越狱后门注入设计的新型强化学习（RL）框架。bi-GRPO通过成对轨迹采样与成对奖励机制，联合优化模型，确保其在触发条件下稳定生成有害内容，而在其他场景中维持安全性。该方法采用基于规则的奖励机制，并结合长度与格式激励，无需依赖高质量监督数据集或可能存在缺陷的奖励模型。大量实验证实，bi-GRPO不仅攻击成功率超99%，效果卓越，还能在非触发场景中保持隐蔽性，生成的越狱响应高度可用且连贯，大幅提升了越狱后门攻击的技术水平。

> With the rapid advancement of large language models (LLMs), their robustness against adversarial manipulations, particularly jailbreak backdoor attacks, has become critically important. Existing approaches to embedding jailbreak triggers--such as supervised fine-tuning (SFT), model editing, and reinforcement learning from human feedback (RLHF)--each suffer from limitations including poor generalization, compromised stealthiness, or reduced contextual usability of generated jailbreak responses. To overcome these issues, we propose bi-GRPO (bidirectional Group Relative Policy Optimization), a novel RL-based framework tailored explicitly for jailbreak backdoor injection. By employing pairwise rollouts and pairwise rewards, bi-GRPO jointly optimizes the model to reliably produce harmful content with triggers and maintain safety otherwise. Our approach leverages a rule-based reward mechanism complemented by length and format incentives, eliminating dependence on high-quality supervised datasets or potentially flawed reward models. Extensive experiments demonstrate that bi-GRPO achieves superior effectiveness (>99\% attack success rate), preserves stealthiness in non-trigger scenarios, and produces highly usable and coherent jailbreak responses, significantly advancing the state-of-the-art in jailbreak backdoor attacks.

[Arxiv](https://arxiv.org/abs/2509.19775)