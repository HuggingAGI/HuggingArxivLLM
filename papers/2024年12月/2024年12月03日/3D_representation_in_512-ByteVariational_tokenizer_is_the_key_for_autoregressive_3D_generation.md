# 在 512 字节中的 3D 表示：变分标记器是自回归 3D 生成的关键所在

发布时间：2024年12月03日

`LLM应用` `3D 生成` `图像生成`

> 3D representation in 512-Byte:Variational tokenizer is the key for autoregressive 3D generation

# 摘要

> 自回归变压器给高保真图像生成带来了革命性的变化。其中的关键在于分词器，它能把高分辨率的图像块压缩成便于大型语言模型处理的离散标记，且采用扫描或分层的顺序。然而，将这类分词器用于 3D 生成时，面临重大挑战：图像块天然具有空间序列和多尺度关系，而 3D 数据没有固有顺序，难以在压缩为更少标记时保留结构细节。为此，我们推出了变分分词器（VAT），它能将无序的 3D 数据转化为具有隐式层次结构的紧凑潜在标记，适用于高效且高保真的从粗到细的自回归建模。VAT 先借助上下文变压器，把大量无序的 3D 特征压缩为信息损失极小的精简标记集。接着，这个潜在空间被映射到高斯分布进行残差量化，标记数量在不同尺度上逐步递增。这样一来，不同尺度的标记通过将自身分配到同一高斯分布内的不同子空间，自然地建立起相互联系，利于跨尺度标记关系的离散建模。在解码阶段，利用高分辨率三面体把这些紧凑的潜在标记转换为精细的 3D 形状。大量实验表明，VAT 能够实现可扩展且高效的 3D 生成，在质量、效率和泛化能力上都优于现有方法。特别值得一提的是，VAT 能实现高达 250 倍的压缩，将 1MB 的网格压缩至仅 3.9KB，F 分数达 96%，还能进一步压缩至 256 个 int8 标记，实现 2000 倍压缩，同时 F 分数保持在 92%。

> Autoregressive transformers have revolutionized high-fidelity image generation. One crucial ingredient lies in the tokenizer, which compresses high-resolution image patches into manageable discrete tokens with a scanning or hierarchical order suitable for large language models. Extending these tokenizers to 3D generation, however, presents a significant challenge: unlike image patches that naturally exhibit spatial sequence and multi-scale relationships, 3D data lacks an inherent order, making it difficult to compress into fewer tokens while preserving structural details. To address this, we introduce the Variational Tokenizer (VAT), which transforms unordered 3D data into compact latent tokens with an implicit hierarchy, suited for efficient and high-fidelity coarse-to-fine autoregressive modeling. VAT begins with an in-context transformer, which compress numerous unordered 3D features into a reduced token set with minimal information loss. This latent space is then mapped to a Gaussian distribution for residual quantization, with token counts progressively increasing across scales. In this way, tokens at different scales naturally establish the interconnections by allocating themselves into different subspaces within the same Gaussian distribution, facilitating discrete modeling of token relationships across scales. During the decoding phase, a high-resolution triplane is utilized to convert these compact latent tokens into detailed 3D shapes. Extensive experiments demonstrate that VAT enables scalable and efficient 3D generation, outperforming existing methods in quality, efficiency, and generalization. Remarkably, VAT achieves up to a 250x compression, reducing a 1MB mesh to just 3.9KB with a 96% F-score, and can further compress to 256 int8 tokens, achieving a 2000x reduction while maintaining a 92% F-score.

[Arxiv](https://arxiv.org/abs/2412.02202)