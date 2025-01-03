# 大型身体语言模型

发布时间：2024年10月21日

`Agent

理由：这篇论文主要讨论了虚拟代理（Agent）在人机交互中的应用，特别是如何通过创新的LBLM架构（LBLM-AVA）来生成逼真且符合上下文的手势。论文的核心内容围绕虚拟代理的实时手势生成能力，属于Agent领域的研究。` `人机交互` `虚拟代理`

> Large Body Language Models

# 摘要

> 随着虚拟代理在人机交互中的广泛应用，实时生成逼真且符合上下文的手势仍是一个重大挑战。尽管神经渲染技术在静态脚本上取得了显著进展，但其在人机交互中的应用仍有限。为此，我们推出了大型身体语言模型（LBLMs），并提出了LBLM-AVA，这是一种创新的LBLM架构，结合了Transformer-XL大型语言模型和并行化扩散模型，能够从多模态输入（文本、音频和视频）生成类人手势。LBLM-AVA集成了多个关键组件，如多模态到姿态嵌入、增强的序列到序列映射、时间平滑模块和基于注意力的细化模块，显著提升了手势生成能力。该模型在我们的大规模开源数据集Allo-AVA上训练，LBLM-AVA在生成逼真且符合上下文的手势方面表现卓越，Fréchet手势距离（FGD）降低了30%，Fréchet起始距离提升了25%，远超现有方法。

> As virtual agents become increasingly prevalent in human-computer interaction, generating realistic and contextually appropriate gestures in real-time remains a significant challenge. While neural rendering techniques have made substantial progress with static scripts, their applicability to human-computer interactions remains limited. To address this, we introduce Large Body Language Models (LBLMs) and present LBLM-AVA, a novel LBLM architecture that combines a Transformer-XL large language model with a parallelized diffusion model to generate human-like gestures from multimodal inputs (text, audio, and video). LBLM-AVA incorporates several key components enhancing its gesture generation capabilities, such as multimodal-to-pose embeddings, enhanced sequence-to-sequence mapping with redefined attention mechanisms, a temporal smoothing module for gesture sequence coherence, and an attention-based refinement module for enhanced realism. The model is trained on our large-scale proprietary open-source dataset Allo-AVA. LBLM-AVA achieves state-of-the-art performance in generating lifelike and contextually appropriate gestures with a 30% reduction in Fréchet Gesture Distance (FGD), and a 25% improvement in Fréchet Inception Distance compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2410.16533)