# LLMs中的幻觉动态：上下文扰动与表征漂移的阴影研究

发布时间：2025年05月22日

`LLM理论`

> Shadows in the Attention: Contextual Perturbation and Representation Drift in the Dynamics of Hallucination in LLMs

# 摘要

> 幻觉现象——看似合理却错误的输出——仍是大型语言模型（LLMs）可靠部署的关键障碍。我们首次系统性地研究了幻觉发生与增量上下文注入引发的内部状态漂移之间的关联。通过TruthfulQA，我们为每个问题构建了两个16轮的“滴定”轨迹：一个附加相关但部分有误的片段，另一个注入蓄意误导的内容。在六种开源LLMs上，我们使用三重视角检测器追踪显性幻觉率，并通过余弦、熵、JS和Spearman漂移分析隐藏状态和注意力图的隐性动态。结果表明：(1)幻觉频率和表征漂移呈现单调增长趋势，在5-7轮后趋于平稳；(2)相关上下文推动深度语义同化，产生高信心的“自我一致”幻觉，而无关上下文则引发以注意力重新路由为特征的主题漂移错误；(3)JS-Drift（约0.69）和Spearman-Drift（约0）的收敛标志着一个“注意力锁定”阈值，超过该阈值后幻觉会固化且难以修正。相关性分析揭示了同化能力和注意力扩散之间的跷跷板效应，阐明了尺寸依赖的错误模式。这些发现为幻觉的内在预测和上下文感知的缓解机制提供了实证基础。

> Hallucinations -- plausible yet erroneous outputs -- remain a critical barrier to reliable deployment of large language models (LLMs). We present the first systematic study linking hallucination incidence to internal-state drift induced by incremental context injection. Using TruthfulQA, we construct two 16-round "titration" tracks per question: one appends relevant but partially flawed snippets, the other injects deliberately misleading content. Across six open-source LLMs, we track overt hallucination rates with a tri-perspective detector and covert dynamics via cosine, entropy, JS and Spearman drifts of hidden states and attention maps. Results reveal (1) monotonic growth of hallucination frequency and representation drift that plateaus after 5--7 rounds; (2) relevant context drives deeper semantic assimilation, producing high-confidence "self-consistent" hallucinations, whereas irrelevant context induces topic-drift errors anchored by attention re-routing; and (3) convergence of JS-Drift ($\sim0.69$) and Spearman-Drift ($\sim0$) marks an "attention-locking" threshold beyond which hallucinations solidify and become resistant to correction. Correlation analyses expose a seesaw between assimilation capacity and attention diffusion, clarifying size-dependent error modes. These findings supply empirical foundations for intrinsic hallucination prediction and context-aware mitigation mechanisms.

[Arxiv](https://arxiv.org/abs/2505.16894)