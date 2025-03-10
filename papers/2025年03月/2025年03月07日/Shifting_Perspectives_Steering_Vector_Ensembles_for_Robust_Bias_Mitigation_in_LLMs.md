# 视角转换：引导向量集合，助力LLMs稳健偏见缓解

发布时间：2025年03月07日

`LLM应用

理由：这篇论文主要探讨了如何通过引导向量和贝叶斯优化来缓解大型语言模型中的偏见问题，属于模型的应用层面，旨在优化模型性能和实际应用效果。因此，归类为LLM应用。` `人工智能` `伦理AI`

> Shifting Perspectives: Steering Vector Ensembles for Robust Bias Mitigation in LLMs

# 摘要

> 我们提出了一种创新的方法，通过在大型语言模型 (LLMs) 的前向传播过程中应用引导向量来修改模型激活，从而有效缓解偏见。我们采用贝叶斯优化系统性地识别了九个偏见轴上的有效对比对数据集。在BBQ数据集上优化后，我们的引导向量分别使Mistral、Llama和Qwen的基线性能平均提升12.2%、4.7%和3.2%。在此基础上，我们提出了引导向量集成 (SVE)，通过平均多个分别针对年龄、种族或性别等特定偏见轴优化的引导向量，实现了更优的偏见缓解效果。SVE不仅显著降低了偏见，还保持了模型性能，优于单独使用引导向量的方法。这是首次系统性研究引导向量在偏见缓解中的应用，证明了SVE是一种强大且计算高效的策略，不仅能够有效减少LLMs中的偏见，还对提升AI安全性具有重要意义。

> We present a novel approach to bias mitigation in large language models (LLMs) by applying steering vectors to modify model activations in forward passes. We employ Bayesian optimization to systematically identify effective contrastive pair datasets across nine bias axes. When optimized on the BBQ dataset, our individually tuned steering vectors achieve average improvements of 12.2%, 4.7%, and 3.2% over the baseline for Mistral, Llama, and Qwen, respectively. Building on these promising results, we introduce Steering Vector Ensembles (SVE), a method that averages multiple individually optimized steering vectors, each targeting a specific bias axis such as age, race, or gender. By leveraging their collective strength, SVE outperforms individual steering vectors in both bias reduction and maintaining model performance. The work presents the first systematic investigation of steering vectors for bias mitigation, and we demonstrate that SVE is a powerful and computationally efficient strategy for reducing bias in LLMs, with broader implications for enhancing AI safety.

[Arxiv](https://arxiv.org/abs/2503.05371)