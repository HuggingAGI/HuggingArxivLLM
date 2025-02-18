# 可调专家混合模型：DeepSeek-R1 推理阶段的行为调整

发布时间：2025年02月16日

`LLM理论` `人工智能`

> Mixture of Tunable Experts - Behavior Modification of DeepSeek-R1 at Inference Time

# 摘要

> 我们提出了混合可调专家（MoTE），这是一种扩展大型语言模型（LLMs）的专家混合架构的方法。无需额外训练，MoTE能够在推理过程中实时调整LLMs的行为，使其更加有意义和有针对性。通过对DeepSeek-R1的数字LLM大脑进行分析，我们采用了一种名为'功能性标记共振成像'（fTRI）的技术（灵感来源于fMRI），并使用了设计用于引发特定行为的提示（例如：'What happened {time}{place}?')，我们实证识别了与拒绝响应等行为相关的独特专家。通过MoTE，我们能够干预并控制这些特定行为。我们关闭了与拒绝行为最相关的前10个专家（占R1 14,848个路由专家的0.07%），在敏感参考提示中实现了52%的拒绝响应减少，同时在MT-Bench基准测试中保持了原有性能。随机专家失活导致的行为变化较小，且噪声增加，而强制专家激活则导致拒绝率显著上升。我们的方法在可解释性和可操控性方面与稀疏自编码器（SAEs）相似。与SAEs不同的是，MoTE不需要大量的训练努力，因为在拥有大量专家的MoEs中，专业化已经在预训练过程中自然形成。我们的发现表明，专家混合架构中重要的功能机制至少可以在少数特定专家中部分定位，而不是分散在整个模型的权重中。专家子组可以被调整以触发显著的行为变化，这为我们深入了解LLMs的内在工作原理提供了见解。

> We present the Mixture-of-Tunable-Experts (MoTE), a method that extends the Mixture-of-Experts architecture of Large Language Models (LLMs). Without additional training, MoTE enables meaningful and focused behavior changes in LLMs on-the-fly during inference time.
  By analyzing the digital LLM brain of DeepSeek-R1 using a technique we dub 'functional Token Resonance Imaging' (fTRI) - inspired by fMRI and using prompts designed to elicit specific behavior (e.g., 'What happened {time}{place}?') - we empirically identify distinctive experts associated with behaviors like refusal responses.
  Using MoTE we are able to intervene and control such specific behavior. We switched off the top 10 most refusal-relevant experts (0.07% of R1's 14,848 routed experts), achieving a 52% refusal reduction on sensitive reference prompts without performance degradation on MT-Bench. Random expert deactivation resulted in smaller behavioral shifts with increased noise, whereas forced expert activation led to significantly higher refusal rates.
  Our approach shares similarities with sparse autoencoders (SAEs) in terms of explainability and steerability. Unlike SAEs, MoTE does not require large training efforts, as within MoEs with a vast number of experts, specialization already emerged naturally during pretraining.
  Our findings suggest that significant functional mechanisms in Mixture-of-Experts architectures can at least partially be localized in a small number of specific experts, rather than being distributed throughout the model's weights. Expert subgroups can be tuned to trigger significant behavior variations, providing insights into the inner workings of LLMs.

[Arxiv](https://arxiv.org/abs/2502.11096)