# # CoCoDiff: 利用粗细文本协同引导的潜在扩散机制，实现骨架动作特征的多样化表达

发布时间：2025年04月29日

`LLM应用` `动作识别` `计算机视觉`

> CoCoDiff: Diversifying Skeleton Action Features via Coarse-Fine Text-Co-Guided Latent Diffusion

# 摘要

> 在动作识别领域，特征多样性是提升模型泛化能力和性能的关键。现有方法通常通过扩展训练数据集来增加特征多样性，但这往往导致效率低下和语义不一致的问题。针对这些挑战，我们提出了创新的粗细文本协同引导扩散模型（CoCoDiff）。该模型利用扩散过程和多粒度文本引导，在潜在空间中生成多样且语义一致的特征表示。具体而言，CoCoDiff将骨架序列中的时空特征输入潜在扩散模型，生成丰富的动作表示。同时，我们设计了一种粗细文本协同引导策略，结合大型语言模型（LLMs）的文本信息，确保生成特征与原始输入在语义上高度一致。值得注意的是，CoCoDiff作为即插即用的辅助模块，在训练过程中无需额外推理成本。实验结果表明，CoCoDiff在NTU RGB+D、NTU RGB+D 120和Kinetics-Skeleton等基准数据集上取得了SOTA级别的优异性能。

> In action recognition tasks, feature diversity is essential for enhancing model generalization and performance. Existing methods typically promote feature diversity by expanding the training data in the sample space, which often leads to inefficiencies and semantic inconsistencies. To overcome these problems, we propose a novel Coarse-fine text co-guidance Diffusion model (CoCoDiff). CoCoDiff generates diverse yet semantically consistent features in the latent space by leveraging diffusion and multi-granularity textual guidance. Specifically, our approach feeds spatio-temporal features extracted from skeleton sequences into a latent diffusion model to generate diverse action representations. Meanwhile, we introduce a coarse-fine text co-guided strategy that leverages textual information from large language models (LLMs) to ensure semantic consistency between the generated features and the original inputs. It is noted that CoCoDiff operates as a plug-and-play auxiliary module during training, incurring no additional inference cost. Extensive experiments demonstrate that CoCoDiff achieves SOTA performance on skeleton-based action recognition benchmarks, including NTU RGB+D, NTU RGB+D 120 and Kinetics-Skeleton.

[Arxiv](https://arxiv.org/abs/2504.21266)