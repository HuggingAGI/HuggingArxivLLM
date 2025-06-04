# MotionRAG-Diff：一种基于检索增强的扩散框架，实现长期音乐到舞蹈生成。

发布时间：2025年06月03日

`RAG` `舞蹈生成` `艺术创作`

> MotionRAG-Diff: A Retrieval-Augmented Diffusion Framework for Long-Term Music-to-Dance Generation

# 摘要

> 生成长期、连贯且逼真的基于音乐的舞蹈序列一直是人类运动合成中的一个难题。现有方法存在明显不足：运动图方法受限于固定模板库，创造力受限；扩散模型虽能生成新颖动作，但常缺乏时间连贯性和音乐对齐。为解决这些挑战，我们提出了【数学公式】，一个结合检索增强生成（RAG）与扩散优化的混合框架，实现高质量、与音乐连贯的舞蹈生成，支持任意长期音乐输入。我们的方法带来三大创新：(1) 跨模态对比学习架构，通过共享潜在空间对齐音乐与舞蹈表示，无需配对数据即可建立语义对应；(2) 优化的运动图系统，高效检索并无缝拼接动作片段，确保长序列真实性和连贯性；(3) 多条件扩散模型，联合利用原始音乐信号和对比特征，提升动作质量和全局同步。实验表明，【数学公式】在动作质量、多样性和音乐-动作同步准确性方面均达顶尖水平。这项工作通过融合基于检索的模板保真度和基于扩散的创造性增强，为音乐驱动的舞蹈生成开辟了新范式。

> Generating long-term, coherent, and realistic music-conditioned dance sequences remains a challenging task in human motion synthesis. Existing approaches exhibit critical limitations: motion graph methods rely on fixed template libraries, restricting creative generation; diffusion models, while capable of producing novel motions, often lack temporal coherence and musical alignment. To address these challenges, we propose $\textbf{MotionRAG-Diff}$, a hybrid framework that integrates Retrieval-Augmented Generation (RAG) with diffusion-based refinement to enable high-quality, musically coherent dance generation for arbitrary long-term music inputs. Our method introduces three core innovations: (1) A cross-modal contrastive learning architecture that aligns heterogeneous music and dance representations in a shared latent space, establishing unsupervised semantic correspondence without paired data; (2) An optimized motion graph system for efficient retrieval and seamless concatenation of motion segments, ensuring realism and temporal coherence across long sequences; (3) A multi-condition diffusion model that jointly conditions on raw music signals and contrastive features to enhance motion quality and global synchronization. Extensive experiments demonstrate that MotionRAG-Diff achieves state-of-the-art performance in motion quality, diversity, and music-motion synchronization accuracy. This work establishes a new paradigm for music-driven dance generation by synergizing retrieval-based template fidelity with diffusion-based creative enhancement.

[Arxiv](https://arxiv.org/abs/2506.02661)