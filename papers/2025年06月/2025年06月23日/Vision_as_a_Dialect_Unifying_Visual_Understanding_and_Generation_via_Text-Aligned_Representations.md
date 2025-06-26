# 视觉作为一门“方言”：通过与文本对齐的表征统一视觉理解和生成能力

发布时间：2025年06月23日

`LLM理论` `计算机视觉`

> Vision as a Dialect: Unifying Visual Understanding and Generation via Text-Aligned Representations

# 摘要

> 本文提出了一种多模态框架，旨在通过共享的离散语义表示统一视觉理解和生成。其核心是文本对齐分词器（TA-Tok），它利用从大型语言模型（LLM）词汇表中投影的文本对齐代码本，将图像转换为离散令牌。通过将视觉和文本整合到一个扩展词汇的统一空间中，我们的多模态LLM——Tar，能够通过共享界面实现跨模态输入和输出，无需特定模态的设计。此外，我们提出了自适应尺度编码和解码以平衡效率和视觉细节，并引入了生成式去分词器以生成高保真视觉输出。为满足多样化的解码需求，我们采用了两种互补的去分词器：快速自回归模型和扩散模型。为了增强模态融合，我们探索了高级预训练任务，展示了在视觉理解和生成方面的提升。在多个基准测试中，Tar的表现与现有方法持平或更优，实现了更快的收敛和更高的训练效率。代码、模型和数据可在https://tar.csuhan.com获取。

> This paper presents a multimodal framework that attempts to unify visual understanding and generation within a shared discrete semantic representation. At its core is the Text-Aligned Tokenizer (TA-Tok), which converts images into discrete tokens using a text-aligned codebook projected from a large language model's (LLM) vocabulary. By integrating vision and text into a unified space with an expanded vocabulary, our multimodal LLM, Tar, enables cross-modal input and output through a shared interface, without the need for modality-specific designs. Additionally, we propose scale-adaptive encoding and decoding to balance efficiency and visual detail, along with a generative de-tokenizer to produce high-fidelity visual outputs. To address diverse decoding needs, we utilize two complementary de-tokenizers: a fast autoregressive model and a diffusion-based model. To enhance modality fusion, we investigate advanced pre-training tasks, demonstrating improvements in both visual understanding and generation. Experiments across benchmarks show that Tar matches or surpasses existing multimodal LLM methods, achieving faster convergence and greater training efficiency. Code, models, and data are available at https://tar.csuhan.com

[Arxiv](https://arxiv.org/abs/2506.18898)