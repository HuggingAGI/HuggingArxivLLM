# 逆向偏好优化在复杂指令执行中的应用

发布时间：2025年05月28日

`LLM应用

摘要讨论了指令遵循（IF）作为大型语言模型（LLMs）的核心能力，并提出了一种新的方法逆偏好优化（RPO）来解决多偏好对齐的问题。该方法通过动态反转指令内的约束，确保所选响应完美无缺，从而减少了大规模采样和筛选的负担。实验结果表明，RPO在多个基准测试中表现优于基线方法，并且在不同模型规模上均表现出色。因此，这篇论文属于LLM应用类别，因为它专注于如何应用和优化LLMs在特定任务中的性能。` `人工智能`

> Reverse Preference Optimization for Complex Instruction Following

# 摘要

> 指令遵循 (IF) 是大型语言模型 (LLMs) 的核心能力，但处理复杂且多约束的指令仍具挑战性。传统方法通过满足约束的数量选择偏好对，但这种选择往往引入噪声：选中的示例可能未完全满足所有约束，而被拒绝的示例可能在某些方面表现更佳。为解决多偏好对齐的难题，我们提出了一种简单而高效的方法——逆偏好优化 (RPO)。该方法通过动态反转指令内的约束，确保所选响应完美无缺，从而减少了大规模采样和筛选的负担。此外，反转操作还扩大了选中与拒绝响应之间的差距，明确了优化方向，使其更具抗噪声能力。我们在 Sysbench 和 Multi-IF 两个多轮 IF 基准测试中评估了 RPO，结果显示其在 Llama-3.1 8B 上分别比 DPO 基线提升了 4.6 和 2.5 个百分点。更值得关注的是，RPO 在不同模型规模（8B 到 70B 参数）上均表现出色，其中 70B 的 RPO 模型性能甚至超越了 GPT-4o。

> Instruction following (IF) is a critical capability for large language models (LLMs). However, handling complex instructions with multiple constraints remains challenging. Previous methods typically select preference pairs based on the number of constraints they satisfy, introducing noise where chosen examples may fail to follow some constraints and rejected examples may excel in certain respects over the chosen ones. To address the challenge of aligning with multiple preferences, we propose a simple yet effective method called Reverse Preference Optimization (RPO). It mitigates noise in preference pairs by dynamically reversing the constraints within the instruction to ensure the chosen response is perfect, alleviating the burden of extensive sampling and filtering to collect perfect responses. Besides, reversal also enlarges the gap between chosen and rejected responses, thereby clarifying the optimization direction and making it more robust to noise. We evaluate RPO on two multi-turn IF benchmarks, Sysbench and Multi-IF, demonstrating average improvements over the DPO baseline of 4.6 and 2.5 points (on Llama-3.1 8B), respectively. Moreover, RPO scales effectively across model sizes (8B to 70B parameters), with the 70B RPO model surpassing GPT-4o.

[Arxiv](https://arxiv.org/abs/2505.22172)