# 面向交互式多模态工具使用智能体的过程监督强化学习

发布时间：2025年09月17日

`Agent` `基础理论`

> Process-Supervised Reinforcement Learning for Interactive Multimodal Tool-Use Agents

# 摘要

> 智能体若要高效使用交互式工具，需掌握工具集成推理（TIR）——这是一个融合多轮规划与长上下文对话管理的复杂过程。为训练智能体应对这一动态过程（尤其是在多模态场景下），我们构建了一个强化学习（RL）沙盒环境，支持语音-文本交错的轨迹生成。我们的核心策略是轮次级裁决强化学习（TARL），它借助大型语言模型（LLM）作为评判者进行轮次级评估，从而攻克了长程任务中的信用分配难题。为提升探索性能，我们将混合任务训练课程与数学推理问题相融合。该统一方法在基于文本的【数学公式】基准测试中，任务通过率较优秀RL基线提升超6%。重要的是，我们验证了该框架可用于微调多模态基础模型以适应智能体任务。通过在语音-文本交错轨迹生成上训练基础多模态LLM，我们赋予其工具使用能力，为构建更自然的语音驱动交互式智能体奠定了基础。

> Effective interactive tool use requires agents to master Tool Integrated Reasoning (TIR): a complex process involving multi-turn planning and long-context dialogue management. To train agents for this dynamic process, particularly in multi-modal contexts, we introduce a sandbox environment for reinforcement learning (RL) that supports interleaved speech-text rollouts. Our core strategy, Turn-level Adjudicated Reinforcement Learning (TARL), addresses the challenge of credit assignment in long-horizon tasks by employing a Large Language Model (LLM) as a judge to provide turn-level evaluation. To enhance exploration, we integrate a mixed-task training curriculum with mathematical reasoning problems. This unified approach boosts the task pass rate on the text-based $τ$-bench by over 6% compared to strong RL baselines. Crucially, we demonstrate our framework's suitability for fine-tuning a multi-modal foundation model for agentic tasks. By training a base multi-modal LLM on interleaved speech-text rollouts, we equip it with tool-use abilities, paving the way for more natural, voice-driven interactive agents.

[Arxiv](https://arxiv.org/abs/2509.14480)