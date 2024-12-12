# AdvWave：针对大型音频语言模型的隐秘对抗式越狱攻击

发布时间：2024年12月11日

`LLM应用` `人工智能`

> AdvWave: Stealthy Adversarial Jailbreak Attack against Large Audio-Language Models

# 摘要

> 近期，大型音频语言模型（LALMs）的发展实现了基于语音的用户交互，极大地提升了用户体验，加快了其在现实应用中的部署。然而，保障 LALMs 的安全性至关重要，以防出现可能引发社会担忧或违反 AI 规定的风险输出。尽管此问题意义重大，但鉴于 LALMs 刚崭露头角，且相比针对基于 DNN 的音频模型的攻击，它带来了更多技术难题，所以关于 LALMs 越狱的研究仍有限。具体而言，LALMs 中的音频编码器涉及离散化操作，常常导致梯度破碎，阻碍了依赖梯度优化的攻击效果。LALMs 的行为多变性也让有效（对抗性）优化目标的确定更为复杂。此外，对对抗性音频波形施加隐秘性约束会引入缩小的、非凸的可行解空间，进一步加大了优化过程的难度。为应对这些挑战，我们开发了 AdvWave，这是首个针对 LALMs 的越狱框架。我们提出了一种双阶段优化方法，解决了梯度破碎问题，实现了有效的端到端基于梯度的优化。另外，我们还开发了一种自适应对抗目标搜索算法，能依据 LALMs 对特定查询的响应模式动态调整对抗优化目标。为确保对抗性音频对人类听众而言在感知上依然自然，我们设计了一种分类器引导的优化方法，生成类似常见城市声音的对抗性噪声。对多个先进的 LALMs 进行的广泛评估显示，AdvWave 优于基线方法，平均越狱攻击成功率提高了 40%。

> Recent advancements in large audio-language models (LALMs) have enabled speech-based user interactions, significantly enhancing user experience and accelerating the deployment of LALMs in real-world applications. However, ensuring the safety of LALMs is crucial to prevent risky outputs that may raise societal concerns or violate AI regulations. Despite the importance of this issue, research on jailbreaking LALMs remains limited due to their recent emergence and the additional technical challenges they present compared to attacks on DNN-based audio models. Specifically, the audio encoders in LALMs, which involve discretization operations, often lead to gradient shattering, hindering the effectiveness of attacks relying on gradient-based optimizations. The behavioral variability of LALMs further complicates the identification of effective (adversarial) optimization targets. Moreover, enforcing stealthiness constraints on adversarial audio waveforms introduces a reduced, non-convex feasible solution space, further intensifying the challenges of the optimization process. To overcome these challenges, we develop AdvWave, the first jailbreak framework against LALMs. We propose a dual-phase optimization method that addresses gradient shattering, enabling effective end-to-end gradient-based optimization. Additionally, we develop an adaptive adversarial target search algorithm that dynamically adjusts the adversarial optimization target based on the response patterns of LALMs for specific queries. To ensure that adversarial audio remains perceptually natural to human listeners, we design a classifier-guided optimization approach that generates adversarial noise resembling common urban sounds. Extensive evaluations on multiple advanced LALMs demonstrate that AdvWave outperforms baseline methods, achieving a 40% higher average jailbreak attack success rate.

[Arxiv](https://arxiv.org/abs/2412.08608)