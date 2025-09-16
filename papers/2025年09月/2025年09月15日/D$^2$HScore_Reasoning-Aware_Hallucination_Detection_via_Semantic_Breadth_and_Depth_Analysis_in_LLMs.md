# D$^2$HScore：基于大型语言模型（LLMs）语义广度与深度分析的推理感知幻觉检测

发布时间：2025年09月15日

`LLM理论` `金融科技` `医疗健康`

> D$^2$HScore: Reasoning-Aware Hallucination Detection via Semantic Breadth and Depth Analysis in LLMs

# 摘要

> 尽管大型语言模型（LLMs）已取得显著成就，但其实际应用常受困于非事实性内容的生成——即所谓的“幻觉”。确保LLMs输出的可靠性是一项关键挑战，尤其在金融、安全和医疗等高风险领域。本研究从模型架构与生成动态的视角重新审视幻觉检测问题。借助LLMs的多层结构与自回归解码机制，我们将幻觉信号拆解为两个互补维度：一是每层token表示的语义广度，二是核心概念在跨层演化中的语义深度。基于这一洞察，我们提出	extbf{【数学公式】（Dispersion and Drift-based Hallucination Score）}——一个无需训练、无标签的框架，它联合度量：(1)	extbf{层内离散度（Intra-Layer Dispersion）}，即量化每层token表示的语义多样性；(2)	extbf{层间漂移（Inter-Layer Drift）}，即追踪关键token表示在跨层中的渐进转变。为确保漂移反映的是有意义语义的演化，而非噪声或冗余token，我们通过注意力信号引导token选择。通过捕捉推理时表示的水平与垂直动态，【数学公式】为幻觉检测提供了可解释、轻量级的代理指标。在五个开源LLM和五个主流基准数据集上的大量实验表明，【数学公式】持续优于现有无需训练基线。

> Although large Language Models (LLMs) have achieved remarkable success, their practical application is often hindered by the generation of non-factual content, which is called "hallucination". Ensuring the reliability of LLMs' outputs is a critical challenge, particularly in high-stakes domains such as finance, security, and healthcare. In this work, we revisit hallucination detection from the perspective of model architecture and generation dynamics. Leveraging the multi-layer structure and autoregressive decoding process of LLMs, we decompose hallucination signals into two complementary dimensions: the semantic breadth of token representations within each layer, and the semantic depth of core concepts as they evolve across layers. Based on this insight, we propose \textbf{D$^2$HScore (Dispersion and Drift-based Hallucination Score)}, a training-free and label-free framework that jointly measures: (1) \textbf{Intra-Layer Dispersion}, which quantifies the semantic diversity of token representations within each layer; and (2) \textbf{Inter-Layer Drift}, which tracks the progressive transformation of key token representations across layers. To ensure drift reflects the evolution of meaningful semantics rather than noisy or redundant tokens, we guide token selection using attention signals. By capturing both the horizontal and vertical dynamics of representation during inference, D$^2$HScore provides an interpretable and lightweight proxy for hallucination detection. Extensive experiments across five open-source LLMs and five widely used benchmarks demonstrate that D$^2$HScore consistently outperforms existing training-free baselines.

[Arxiv](https://arxiv.org/abs/2509.11569)