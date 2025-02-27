# 稀疏大脑同样具备适应性：感知认知负荷的LLM动态激活机制

发布时间：2025年02月26日

`LLM应用

摘要讨论了CLADA框架，旨在通过动态激活优化大语言模型的效率，属于实际应用层面的改进。` `人工智能` `认知科学`

> Sparse Brains are Also Adaptive Brains: Cognitive-Load-Aware Dynamic Activation for LLMs

# 摘要

> 密集型大语言模型（LLMs）在效率上面临严重瓶颈，因为它们 rigidly activate all parameters regardless of input complexity。现有的稀疏性方法（static pruning 或 dynamic activation）仅部分解决了这一问题，它们要么缺乏对上下文或模型结构需求的适应性，要么带来过高的计算开销。受人类大脑的双过程机制启发——预测编码（N400）用于骨干稀疏性，结构再分析（P600）用于复杂上下文，我们提出了 CLADA，一个 	extit{	extbf{C}ognitive-	extbf{L}oad-	extbf{A}ware 	extbf{D}ynamic 	extbf{A}ctivation} 框架，将统计稀疏性与语义适应性相结合。我们的关键见解是，LLM 激活表现出两种互补模式：1) 由序列级前缀信息驱动的 	extit{全局统计稀疏性}，以及 2) 由认知负荷指标（如 surprisal 和 entropy）调节的 	extit{局部语义适应性}。CLADA 采用分层阈值策略：通过离线误差控制优化设置基线，确保 40\%+ 的稀疏性，并通过实时认知信号进行动态调整。在六种主流 LLM 和九个基准上的评估表明，CLADA 实现了 	extbf{~20\% 的平均加速，同时仅损失 <2\% 的准确性}，优于 Griffin（5\%+ 的性能下降）和 TT（几乎无加速）。至关重要的是，通过多级回归分析（$R^2=0.17$ for sparsity-adaptation synergy），我们首次正式建立了神经语言学事件相关电位（ERP）成分与 LLM 效率机制之间的联系。无需重新训练或架构更改，CLADA 为资源感知的 LLM 推理提供了一个可部署的解决方案，同时推动了生物启发式 AI 设计的发展。我们的代码可在 \href{https://github.com/Oldify/CLADA}{CLADA} 获取。


> Dense large language models(LLMs) face critical efficiency bottlenecks as they rigidly activate all parameters regardless of input complexity. While existing sparsity methods(static pruning or dynamic activation) address this partially, they either lack adaptivity to contextual or model structural demands or incur prohibitive computational overhead. Inspired by human brain's dual-process mechanisms - predictive coding (N400) for backbone sparsity and structural reanalysis (P600) for complex context - we propose CLADA, a \textit{\textbf{C}ognitive-\textbf{L}oad-\textbf{A}ware \textbf{D}ynamic \textbf{A}ctivation} framework that synergizes statistical sparsity with semantic adaptability. Our key insight is that LLM activations exhibit two complementary patterns: 1) \textit{Global statistical sparsity} driven by sequence-level prefix information, and 2) \textit{Local semantic adaptability} modulated by cognitive load metrics(e.g., surprisal and entropy). CLADA employs a hierarchical thresholding strategy: a baseline from offline error-controlled optimization ensures 40\%+ sparsity, dynamically adjusted by real-time cognitive signals. Evaluations across six mainstream LLMs and nine benchmarks demonstrate that CLADA achieves \textbf{~20\% average speedup with <2\% accuracy drop}, outperforming Griffin (5\%+ degradation) and TT (negligible speedup). Crucially, we establish the first formal connection between neurolinguistic event-related potential (ERP) components and LLM efficiency mechanisms through multi-level regression analysis ($R^2=0.17$ for sparsity-adaptation synergy). Requiring no retraining or architectural changes, CLADA offers a deployable solution for resource-aware LLM inference while advancing biologically-inspired AI design. Our code is available at \href{https://github.com/Oldify/CLADA}{CLADA}.

[Arxiv](https://arxiv.org/abs/2502.19078)