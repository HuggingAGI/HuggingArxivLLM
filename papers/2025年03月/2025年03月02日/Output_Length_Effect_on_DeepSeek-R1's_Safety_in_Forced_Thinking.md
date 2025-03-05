# 输出长度对 DeepSeek-R1 强制思考安全性的影响

发布时间：2025年03月02日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在对抗条件下的安全性，特别是输出长度对模型鲁棒性的影响。研究通过分析对抗提示的响应，提出了基于强化学习的策略调整和自适应令牌长度调节方法，以提升模型的安全性。这属于对LLM内在机制的理论研究和改进，因此归类为LLM理论。` `计算机安全` `人工智能`

> Output Length Effect on DeepSeek-R1's Safety in Forced Thinking

# 摘要

> 大型语言模型（LLMs）拥有强大的推理能力，但其在对抗条件下的安全性仍需改进。本研究聚焦于输出长度对DeepSeek-R1模型鲁棒性的影响，特别是在强制思考场景中。通过对多种对抗提示的响应分析，我们发现：较长的输出虽然能通过自我修正提升安全性，但也可能被某些攻击方式所利用。研究结果表明，动态控制输出长度是平衡推理效果与安全性的关键。为此，我们提出基于强化学习的策略调整和自适应令牌长度调节方法，以有效提升LLMs的安全性。

> Large Language Models (LLMs) have demonstrated strong reasoning capabilities, but their safety under adversarial conditions remains a challenge. This study examines the impact of output length on the robustness of DeepSeek-R1, particularly in Forced Thinking scenarios. We analyze responses across various adversarial prompts and find that while longer outputs can improve safety through self-correction, certain attack types exploit extended generations. Our findings suggest that output length should be dynamically controlled to balance reasoning effectiveness and security. We propose reinforcement learning-based policy adjustments and adaptive token length regulation to enhance LLM safety.

[Arxiv](https://arxiv.org/abs/2503.01923)