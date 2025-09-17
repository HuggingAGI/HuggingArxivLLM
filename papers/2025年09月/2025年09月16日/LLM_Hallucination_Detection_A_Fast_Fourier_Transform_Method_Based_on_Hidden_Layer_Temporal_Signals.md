# LLM幻觉检测：基于隐藏层时间信号的快速傅里叶变换方法

发布时间：2025年09月16日

`LLM应用` `基础理论`

> LLM Hallucination Detection: A Fast Fourier Transform Method Based on Hidden Layer Temporal Signals

# 摘要

> 幻觉问题仍是大型语言模型（LLMs）在可靠性敏感应用中部署的关键障碍。现有检测方法大致分为两类：一类是事实核查，但其效果本质上受限于外部知识的覆盖范围；另一类是静态隐藏状态分析，却无法捕捉推理动态中的偏差。因此，这些方法的有效性和稳健性仍有局限。为此，我们提出了HSAD（基于隐藏信号分析的检测）——一种新颖的幻觉检测框架，它能对自回归生成过程中隐藏表示的时间动态进行建模。HSAD通过跨层采样激活值构建隐藏层信号，再应用快速傅里叶变换（FFT）得到频域表示，最后提取最强的非直流（non-DC）频率分量作为频谱特征。此外，HSAD还利用LLMs的自回归特性，确定了有效且可靠检测的最佳观察点。在包括TruthfulQA在内的多个基准测试中，HSAD相较以往的最先进方法，性能提升超过10个百分点。通过融合推理过程建模与频域分析，HSAD为LLMs的稳健幻觉检测开创了新范式。

> Hallucination remains a critical barrier for deploying large language models (LLMs) in reliability-sensitive applications. Existing detection methods largely fall into two categories: factuality checking, which is fundamentally constrained by external knowledge coverage, and static hidden-state analysis, that fails to capture deviations in reasoning dynamics. As a result, their effectiveness and robustness remain limited. We propose HSAD (Hidden Signal Analysis-based Detection), a novel hallucination detection framework that models the temporal dynamics of hidden representations during autoregressive generation. HSAD constructs hidden-layer signals by sampling activations across layers, applies Fast Fourier Transform (FFT) to obtain frequency-domain representations, and extracts the strongest non-DC frequency component as spectral features. Furthermore, by leveraging the autoregressive nature of LLMs, HSAD identifies optimal observation points for effective and reliable detection. Across multiple benchmarks, including TruthfulQA, HSAD achieves over 10 percentage points improvement compared to prior state-of-the-art methods. By integrating reasoning-process modeling with frequency-domain analysis, HSAD establishes a new paradigm for robust hallucination detection in LLMs.

[Arxiv](https://arxiv.org/abs/2509.13154)