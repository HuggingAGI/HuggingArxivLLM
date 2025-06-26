# # 机制解释性在架构模糊中的探讨

发布时间：2025年06月22日

`LLM理论` `隐私保护` `人工智能`

> Mechanistic Interpretability in the Presence of Architectural Obfuscation

# 摘要

> 架构模糊化——如置换隐藏状态张量、线性变换嵌入表或重新映射令牌——最近作为一种轻量级替代方案，用于替代隐私保护大型语言模型（LLM）推理中的重量级加密技术。尽管近期研究表明这些技术在定向重构攻击下可被破解，但它们对模型可解释性的影响尚未得到系统性研究。特别地，尚不清楚扰乱网络内部表示是否真正阻碍了理解模型工作原理，还是仅将其重新定位到一个陌生的坐标系。我们通过分析一个从零开始训练的 GPT-2-small 模型，采用具有代表性的模糊化映射，来填补这一研究空白。假设模糊化映射是私有的，且原始基向量被隐藏（模拟诚实但好奇的服务器），我们应用了 logit-lens 归因、因果路径修补和注意力头消融等方法，以定位和操作已知的电路。我们的研究发现，模糊化显著改变了注意力头内的激活模式，却保留了逐层的计算图。这种脱节阻碍了用户提示的逆向工程：因果轨迹与基线语义失去对齐，而基于令牌的 logit 归因变得过于嘈杂，无法进行重构。同时，前馈和残差通路在功能上保持完整，表明模糊化降低了细粒度的可解释性，而没有损害顶层任务性能。这些结果提供了定量证据，证明架构模糊化可以同时 (i) 保留全局模型行为和 (ii) 阻碍对用户特定内容的机制分析。通过映射可解释性失效的位置，我们的研究为未来的隐私防御和鲁棒性感知的可解释性工具提供了指导。

> Architectural obfuscation - e.g., permuting hidden-state tensors, linearly transforming embedding tables, or remapping tokens - has recently gained traction as a lightweight substitute for heavyweight cryptography in privacy-preserving large-language-model (LLM) inference. While recent work has shown that these techniques can be broken under dedicated reconstruction attacks, their impact on mechanistic interpretability has not been systematically studied. In particular, it remains unclear whether scrambling a network's internal representations truly thwarts efforts to understand how the model works, or simply relocates the same circuits to an unfamiliar coordinate system. We address this gap by analyzing a GPT-2-small model trained from scratch with a representative obfuscation map. Assuming the obfuscation map is private and the original basis is hidden (mirroring an honest-but-curious server), we apply logit-lens attribution, causal path-patching, and attention-head ablation to locate and manipulate known circuits. Our findings reveal that obfuscation dramatically alters activation patterns within attention heads yet preserves the layer-wise computational graph. This disconnect hampers reverse-engineering of user prompts: causal traces lose their alignment with baseline semantics, and token-level logit attributions become too noisy to reconstruct. At the same time, feed-forward and residual pathways remain functionally intact, suggesting that obfuscation degrades fine-grained interpretability without compromising top-level task performance. These results establish quantitative evidence that architectural obfuscation can simultaneously (i) retain global model behaviour and (ii) impede mechanistic analyses of user-specific content. By mapping where interpretability breaks down, our study provides guidance for future privacy defences and for robustness-aware interpretability tooling.

[Arxiv](https://arxiv.org/abs/2506.18053)