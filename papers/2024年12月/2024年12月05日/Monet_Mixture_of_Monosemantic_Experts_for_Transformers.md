# 莫奈：Transformer 的单义专家混合体

发布时间：2024年12月05日

`LLM理论` `语言模型` `人工智能`

> Monet: Mixture of Monosemantic Experts for Transformers

# 摘要

> 理解大型语言模型（LLMs）的内部运算对于让其与人类价值观相符以及避免诸如生成有害内容之类的不良行为至关重要。然而，多义性成了机械可解释性的阻碍——单个神经元会对多个不相关的概念产生反应。尽管稀疏自编码器（SAEs）试图通过稀疏字典学习来理清这些特征，但因其依赖事后重建损失而影响了LLM的性能。为解决此问题，我们推出了用于Transformer的单义专家混合（Monet）架构，将稀疏字典学习直接融入端到端的专家混合预训练中。我们创新的专家分解方法能够把每层的专家数量增加到262,144，而总参数则与专家数量的平方根成正比地增加。我们的分析显示专家之间的知识相互排斥，并展示了单个专家所包含的参数知识。此外，Monet允许在不降低整体性能的情况下对领域、语言和毒性减轻进行知识操作。我们对透明LLM的探索凸显了增加专家数量以增强机械可解释性以及直接切除内部知识以从根本上调整模型行为的潜力。源代码和预训练检查点可在https://github.com/dmis-lab/Monet获取。

> Understanding the internal computations of large language models (LLMs) is crucial for aligning them with human values and preventing undesirable behaviors like toxic content generation. However, mechanistic interpretability is hindered by polysemanticity -- where individual neurons respond to multiple, unrelated concepts. While Sparse Autoencoders (SAEs) have attempted to disentangle these features through sparse dictionary learning, they have compromised LLM performance due to reliance on post-hoc reconstruction loss. To address this issue, we introduce Mixture of Monosemantic Experts for Transformers (Monet) architecture, which incorporates sparse dictionary learning directly into end-to-end Mixture-of-Experts pretraining. Our novel expert decomposition method enables scaling the expert count to 262,144 per layer while total parameters scale proportionally to the square root of the number of experts. Our analyses demonstrate mutual exclusivity of knowledge across experts and showcase the parametric knowledge encapsulated within individual experts. Moreover, Monet allows knowledge manipulation over domains, languages, and toxicity mitigation without degrading general performance. Our pursuit of transparent LLMs highlights the potential of scaling expert counts to enhance} mechanistic interpretability and directly resect the internal knowledge to fundamentally adjust} model behavior. The source code and pretrained checkpoints are available at https://github.com/dmis-lab/Monet.

[Arxiv](https://arxiv.org/abs/2412.04139)