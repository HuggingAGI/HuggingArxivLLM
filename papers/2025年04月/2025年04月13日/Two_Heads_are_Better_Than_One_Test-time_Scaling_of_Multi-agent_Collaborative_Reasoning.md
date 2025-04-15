# 双管齐下：多智能体推理协作的测试时扩展研究

发布时间：2025年04月13日

`Agent` `人工智能` `多智能体系统`

> Two Heads are Better Than One: Test-time Scaling of Multi-agent Collaborative Reasoning

# 摘要

> 基于大型语言模型（LLMs）的多智能体系统（MAS）为解决复杂现实任务提供了新思路，超越了传统单智能体系统的局限。尽管测试时扩展（TTS）技术显著提升了单智能体在复杂推理任务中的表现，但多智能体协作推理的扩展仍面临诸多挑战。我们提出了一种自适应多智能体框架，通过模型训练与系统协调的双重优化来提升协作推理能力。构建的M500数据集包含500个多智能体协作推理轨迹，基于此微调Qwen2.5-32B-Instruct模型，打造了专门针对多智能体协作优化的M1-32B模型。为实现更智能的自适应推理，我们设计了一种新型CEO智能体，能够动态管理讨论流程，优化协作模式，并根据需要调整推理深度，从而更高效地解决问题。在开源MAS系统中，我们针对通用理解、数学推理和编程等多类任务进行了全面评估，结果显示我们的系统显著超越了现有基线模型。例如，M1-32B在GPQA-Diamond任务上提升了12%，在AIME2024任务上提升了41%，在MBPP-Sanitized任务上提升了10%，并在部分任务上达到了DeepSeek-R1等最先进模型的性能水平。这些结果充分证明了学习型协作与自适应协调在扩展多智能体推理中的关键作用。更多代码与资源可访问https://github.com/jincan333/MAS-TTS获取。

> Multi-agent systems (MAS) built on large language models (LLMs) offer a promising path toward solving complex, real-world tasks that single-agent systems often struggle to manage. While recent advancements in test-time scaling (TTS) have significantly improved single-agent performance on challenging reasoning tasks, how to effectively scale collaboration and reasoning in MAS remains an open question. In this work, we introduce an adaptive multi-agent framework designed to enhance collaborative reasoning through both model-level training and system-level coordination. We construct M500, a high-quality dataset containing 500 multi-agent collaborative reasoning traces, and fine-tune Qwen2.5-32B-Instruct on this dataset to produce M1-32B, a model optimized for multi-agent collaboration. To further enable adaptive reasoning, we propose a novel CEO agent that dynamically manages the discussion process, guiding agent collaboration and adjusting reasoning depth for more effective problem-solving. Evaluated in an open-source MAS across a range of tasks-including general understanding, mathematical reasoning, and coding-our system significantly outperforms strong baselines. For instance, M1-32B achieves 12% improvement on GPQA-Diamond, 41% on AIME2024, and 10% on MBPP-Sanitized, matching the performance of state-of-the-art models like DeepSeek-R1 on some tasks. These results highlight the importance of both learned collaboration and adaptive coordination in scaling multi-agent reasoning. Code is available at https://github.com/jincan333/MAS-TTS

[Arxiv](https://arxiv.org/abs/2504.09772)