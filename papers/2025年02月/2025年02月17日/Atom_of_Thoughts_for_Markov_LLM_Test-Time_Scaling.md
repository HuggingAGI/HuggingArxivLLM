# # 思考的原子：马尔可夫语言模型测试时的思维原子缩放

发布时间：2025年02月17日

`LLM理论

摘要讨论了大型语言模型（LLMs）推理时的扩展问题，并提出了一种新的推理方法Atom of Thoughts (AoT)。该方法通过分解推理过程为独立的子问题，类似于马尔可夫过程，从而减少对历史信息的依赖。论文重点在于提出理论方法和改进推理机制，因此归类为LLM理论。` `问答系统`

> Atom of Thoughts for Markov LLM Test-Time Scaling

# 摘要

> 大型语言模型（LLMs）凭借训练时间扩展实现了卓越性能，推理时扩展则通过在推理过程中进行有效推理进一步提升能力。然而，随着推理规模的扩大，现有推理时扩展方法面临历史信息积累的问题，这不仅浪费计算资源，还干扰有效推理。为解决这一问题，我们发现复杂推理过程通常通过解决一系列独立的子问题来实现，每个子问题都是自洽且可验证的。这些子问题本质上是原子问题，主要依赖当前状态而非历史积累，类似于马尔可夫过程中的无记忆转换。基于此观察，我们提出Atom of Thoughts (AoT)，其中推理过程中的每个状态转换包括将当前问题分解为基于依赖关系的有向无环图，并将其子问题收缩形成新的原子问题状态。这一迭代分解-收缩过程持续进行，直至达到可直接解答的原子问题，从而自然实现问题状态间的马尔可夫转换。此外，这些原子问题可无缝集成到现有推理时扩展方法中，使AoT能够作为插件增强推理能力。在六个基准上的实验表明，AoT作为独立框架或插件增强均表现出有效性。值得注意的是，在HotpotQA上，AoT应用于gpt-4o-mini时，实现了80.6%的F1分数，比o3-mini高出3.4%，比DeepSeek-R1高出10.6%。代码将在https://github.com/qixucen/atom上提供。


> Large Language Models (LLMs) achieve superior performance through training-time scaling, and test-time scaling further enhances their capabilities by conducting effective reasoning during inference. However, as the scale of reasoning increases, existing test-time scaling methods suffer from accumulated historical information, which not only wastes computational resources but also interferes with effective reasoning. To address this issue, we observe that complex reasoning progress is often achieved by solving a sequence of independent subquestions, each being self-contained and verifiable. These subquestions are essentially atomic questions, relying primarily on their current state rather than accumulated history, similar to the memoryless transitions in a Markov process. Based on this observation, we propose Atom of Thoughts (AoT), where each state transition in the reasoning process consists of decomposing the current question into a dependency-based directed acyclic graph and contracting its subquestions, forming a new atomic question state. This iterative decomposition-contraction process continues until reaching directly solvable atomic questions, naturally realizing Markov transitions between question states. Furthermore, these atomic questions can be seamlessly integrated into existing test-time scaling methods, enabling AoT to serve as a plug-in enhancement for improving reasoning capabilities. Experiments across six benchmarks demonstrate the effectiveness of AoT both as a standalone framework and a plug-in enhancement. Notably, on HotpotQA, when applied to gpt-4o-mini, AoT achieves an 80.6% F1 score, surpassing o3-mini by 3.4% and DeepSeek-R1 by 10.6%. The code will be available at https://github.com/qixucen/atom.

[Arxiv](https://arxiv.org/abs/2502.12018)