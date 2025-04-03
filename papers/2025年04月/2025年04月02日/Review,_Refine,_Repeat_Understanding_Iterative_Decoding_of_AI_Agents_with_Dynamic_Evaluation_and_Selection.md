# 复盘、精进、再出发：探索AI智能体迭代解码机制：动态评估与选择

发布时间：2025年04月02日

`LLM应用` `人工智能` `优化方法`

> Review, Refine, Repeat: Understanding Iterative Decoding of AI Agents with Dynamic Evaluation and Selection

# 摘要

> AI 代理在多模态应用、结构化生成和战略规划领域仍面临挑战，传统微调方法在此类任务中效果有限。Best-of-N 采样虽能提升性能，但缺乏反馈机制。为此，我们提出迭代代理解码 (IAD)，通过验证器引导的动态候选评估与选择，结合迭代细化，最大化利用奖励分数。在 Sketch2Code、Text2SQL 和 Webshop 上，IAD 表现优于传统方法，分别在 Sketch2Code 和 Text2SQL 上实现 3-6% 的绝对增益，在 Webshop 上实现 8-10% 的增益。实验表明，IAD 的优势主要源于验证器引导的细化，而非采样多样性。此外，IAD 和 BON 在最优验证器引导下均表现出推理时的计算量增加。分析显示，验证器质量对推理时优化至关重要，噪声和稀疏奖励会影响扩展行为。这些发现为推理时优化的权衡和原则提供了关键见解。

> While AI agents have shown remarkable performance at various tasks, they still struggle with complex multi-modal applications, structured generation and strategic planning. Improvements via standard fine-tuning is often impractical, as solving agentic tasks usually relies on black box API access without control over model parameters. Inference-time methods such as Best-of-N (BON) sampling offer a simple yet effective alternative to improve performance. However, BON lacks iterative feedback integration mechanism. Hence, we propose Iterative Agent Decoding (IAD) which combines iterative refinement with dynamic candidate evaluation and selection guided by a verifier. IAD differs in how feedback is designed and integrated, specifically optimized to extract maximal signal from reward scores. We conduct a detailed comparison of baselines across key metrics on Sketch2Code, Text2SQL, and Webshop where IAD consistently outperforms baselines, achieving 3--6% absolute gains on Sketch2Code and Text2SQL (with and without LLM judges) and 8--10% gains on Webshop across multiple metrics. To better understand the source of IAD's gains, we perform controlled experiments to disentangle the effect of adaptive feedback from stochastic sampling, and find that IAD's improvements are primarily driven by verifier-guided refinement, not merely sampling diversity. We also show that both IAD and BON exhibit inference-time scaling with increased compute when guided by an optimal verifier. Our analysis highlights the critical role of verifier quality in effective inference-time optimization and examines the impact of noisy and sparse rewards on scaling behavior. Together, these findings offer key insights into the trade-offs and principles of effective inference-time optimization.

[Arxiv](https://arxiv.org/abs/2504.01931)