# # 匹配市场遇上大语言模型：基于排序偏好的算法推理
匹配市场与大语言模型 (LLMs) 的结合展现了算法推理的潜力，通过分析排序偏好来优化决策过程。

发布时间：2025年06月04日

`LLM应用

LLM应用` `资源管理`

> Matching Markets Meet LLMs: Algorithmic Reasoning with Ranked Preferences

# 摘要

> 大型语言模型（LLMs）的崛起推动了从程序合成到科学假设生成等推理任务的发展，但在处理组合域中的排名偏好和结构化算法方面，其能力仍有待深入探索。我们聚焦于匹配市场这一核心框架，它广泛应用于资源分配和拼车等场景，这些场景需要协调个体排名偏好以确保稳定结果。我们通过一系列基于偏好的推理任务，从稳定匹配生成到不稳定性的检测、解决以及细粒度偏好查询，系统评估了多个先进模型的表现，揭示了它们在处理排名输入时的逻辑与算法局限性。令人惊讶的是，即使是最先进的顶级模型，在大型市场中也难以有效解决不稳定性问题，常常无法识别阻塞对或迭代执行算法。我们进一步发现，参数高效的微调（如LoRA）虽能显著提升小型市场的性能，但在大型实例上效果有限，这表明需要更 sophisticated 的策略来增强 LLMs 处理更大上下文输入的推理能力。

> The rise of Large Language Models (LLMs) has driven progress in reasoning tasks -- from program synthesis to scientific hypothesis generation -- yet their ability to handle ranked preferences and structured algorithms in combinatorial domains remains underexplored. We study matching markets, a core framework behind applications like resource allocation and ride-sharing, which require reconciling individual ranked preferences to ensure stable outcomes. We evaluate several state-of-the-art models on a hierarchy of preference-based reasoning tasks -- ranging from stable-matching generation to instability detection, instability resolution, and fine-grained preference queries -- to systematically expose their logical and algorithmic limitations in handling ranked inputs. Surprisingly, even top-performing models with advanced reasoning struggle to resolve instability in large markets, often failing to identify blocking pairs or execute algorithms iteratively. We further show that parameter-efficient fine-tuning (LoRA) significantly improves performance in small markets, but fails to bring about a similar improvement on large instances, suggesting the need for more sophisticated strategies to improve LLMs' reasoning with larger-context inputs.

[Arxiv](https://arxiv.org/abs/2506.04478)