# 学习自然语言约束，实现语言智能体的安全强化学习

发布时间：2025年04月04日

`LLM应用` `人工智能安全`

> Learning Natural Language Constraints for Safe Reinforcement Learning of Language Agents

# 摘要

> 通用对齐是将大型语言模型（LLMs）安全应用于现实世界NLP任务的核心挑战。当前的对齐方法，如基于人类反馈的强化学习（RLHF），由于依赖隐式的偏好反馈，往往无法在训练分布之外保证约束满足。受到一种范式转变的启发，即先整理数据再进行模型调整，我们提出了一种新的安全语言对齐框架。该框架首先从正向和反向演示中学习自然语言约束。通过推断任务特定的奖励函数和潜在的约束函数，我们的方法能够适应新型安全需求，并在领域变化和对抗输入下实现稳健的泛化。我们在这个框架内形式化为一个约束马尔可夫决策过程（CMDP），并通过一个基于文本的导航环境进行了验证，展示了对不断变化的危险区域的安全适应。实验结果表明，在领域变化时，遵循安全导航路径的违规行为显著减少。此外，通过将学习到的约束应用于蒸馏BERT模型作为微调技术，我们实现了零违规。这项工作为构建安全关键且更具通用性的LLMs提供了有前景的路径，适用于实际的NLP场景。

> Generalizable alignment is a core challenge for deploying Large Language Models (LLMs) safely in real-world NLP applications. Current alignment methods, including Reinforcement Learning from Human Feedback (RLHF), often fail to guarantee constraint satisfaction outside their training distribution due to their reliance on implicit, post-hoc preferences. Inspired by a paradigm shift to first curate data before tuning, we introduce a new framework for safe language alignment that learns natural language constraints from positive and negative demonstrations as a primary step. From inferring both a task-specific reward function and latent constraint functions, our approach fosters adaptation to novel safety requirements and robust generalization under domain shifts and adversarial inputs. We formalize the framework within a Constrained Markov Decision Process (CMDP) and validate it via a text-based navigation environment, demonstrating safe adaptation to changing danger zones. Our experiments show fewer violations upon domain shift when following a safe navigation path, and we achieve zero violations by applying learned constraints to a distilled BERT model as a fine-tuning technique. This work offers a promising path toward building safety-critical and more generalizable LLMs for practical NLP settings.

[Arxiv](https://arxiv.org/abs/2504.03185)