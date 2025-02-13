# 网络智能体的共生协作：充分发挥大模型与小模型的互补优势

发布时间：2025年02月11日

`LLM应用

摘要讨论了大型语言模型（LLMs）在Web浏览代理中的应用，提出了一种结合大型和小型LLMs的框架，以提升任务性能和数据合成。研究重点在于LLMs的应用和优化，因此归类为LLM应用。` `自动化` `人工智能`

> Symbiotic Cooperation for Web Agents: Harnessing Complementary Strengths of Large and Small LLMs

# 摘要

> 基于大型语言模型（LLMs）的Web浏览代理在自动化复杂网络任务方面展现出巨大潜力。现有方法通常依赖大型LLMs（如GPT-4o）探索网络环境并生成轨迹数据，这些数据随后用于演示检索（针对大型LLMs）或蒸馏小型LLMs（如Llama3），但这一过程与探索环节脱钩。本文中，我们提出了AgentSymbiotic，一个将数据合成与任务性能相结合的迭代框架，实现大型和小型LLMs的"共生改进"。研究发现，LLM类型之间存在互补动态：大型LLMs擅长生成高质量的蒸馏轨迹，而蒸馏后的小型LLMs由于其独特的推理能力，往往选择与大型模型不同的动作。这种差异推动了新型轨迹的探索，从而丰富了合成数据。然而，我们也观察到小型LLMs的性能在此迭代增强过程中成为瓶颈。为此，我们在LLM蒸馏中提出了两项创新：一种缓解策略偏差的推测式数据合成策略，以及一种提升学生LLM推理能力的多任务学习方法。此外，我们引入了一种隐私保护的混合模式以应对用户隐私担忧。在WEBARENA基准测试中，AgentSymbiotic实现了两种LLM类型的最先进性能。我们的大型LLM最佳代理达到52%的性能，超越了之前的最佳水平45%，而8B蒸馏模型也展现了49%的竞争力，超过了之前的最佳水平28%。代码将在论文接收后发布。

> Web browsing agents powered by large language models (LLMs) have shown tremendous potential in automating complex web-based tasks. Existing approaches typically rely on large LLMs (e.g., GPT-4o) to explore web environments and generate trajectory data, which is then used either for demonstration retrieval (for large LLMs) or to distill small LLMs (e.g., Llama3) in a process that remains decoupled from the exploration. In this paper, we propose AgentSymbiotic, an iterative framework that couples data synthesis with task-performance, yielding a "symbiotic improvement" for both large and small LLMs. Our study uncovers a complementary dynamic between LLM types: while large LLMs excel at generating high-quality trajectories for distillation, the distilled small LLMs-owing to their distinct reasoning capabilities-often choose actions that diverge from those of their larger counterparts. This divergence drives the exploration of novel trajectories, thereby enriching the synthesized data. However, we also observe that the performance of small LLMs becomes a bottleneck in this iterative enhancement process. To address this, we propose two innovations in LLM distillation: a speculative data synthesis strategy that mitigates off-policy bias, and a multi-task learning approach designed to boost the reasoning capabilities of the student LLM. Furthermore, we introduce a Hybrid Mode for Privacy Preservation to address user privacy concerns. Evaluated on the WEBARENA benchmark, AgentSymbiotic achieves SOTA performance with both LLM types. Our best Large LLM agent reaches 52%, surpassing the previous best of 45%, while our 8B distilled model demonstrates a competitive 49%, exceeding the prior best of 28%. Code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2502.07942)