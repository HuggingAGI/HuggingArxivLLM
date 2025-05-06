# VAEmo：高效视觉音频情感表示学习，融入知识注入

发布时间：2025年05月04日

`LLM应用`

> VAEmo: Efficient Representation Learning for Visual-Audio Emotion with Knowledge Injection

# 摘要

> 音频视觉情感识别 (AVER) 通过非语言的视听 (VA) 信息推断人类情感，具有模态互补与语言无关的独特优势。然而，由于情感表达的固有模糊性、跨模态表达差异以及可靠标注数据的稀缺性，AVER 仍面临诸多挑战。近期的自监督 AVER 方法虽引入了强大的多模态表示，但主要依赖模态特定编码器和粗略内容级对齐，限制了细粒度情感语义建模。为解决这些问题，我们提出 VAEmo，一个高效的两阶段框架，用于以情感为中心的联合 VA 表示学习，并引入外部知识注入。在第一阶段，通过在大规模以说话者为中心的视听语料库上进行掩蔽重构和对比目标预训练，构建了一个统一且轻量化的表示网络，有效缓解模态间差距，并在无情感标签的情况下学习表达性互补表示。第二阶段，多模态大型语言模型根据我们精心设计的链式思考提示，为少量 VA 样本自动生成详细情感描述；随后通过双路径对比学习将这些丰富的文本语义与 VA 表示对齐，进一步弥合情感差距。在多个下游 AVER 基准上的广泛实验表明，VAEmo 以紧凑设计实现了最先进的性能，突显了统一跨模态编码与情感感知语义引导对高效、通用 VA 情感表示的益处。

> Audiovisual emotion recognition (AVER) aims to infer human emotions from nonverbal visual-audio (VA) cues, offering modality-complementary and language-agnostic advantages. However, AVER remains challenging due to the inherent ambiguity of emotional expressions, cross-modal expressive disparities, and the scarcity of reliably annotated data. Recent self-supervised AVER approaches have introduced strong multimodal representations, yet they predominantly rely on modality-specific encoders and coarse content-level alignment, limiting fine-grained emotional semantic modeling. To address these issues, we propose VAEmo, an efficient two-stage framework for emotion-centric joint VA representation learning with external knowledge injection. In Stage 1, a unified and lightweight representation network is pre-trained on large-scale speaker-centric VA corpora via masked reconstruction and contrastive objectives, mitigating the modality gap and learning expressive, complementary representations without emotion labels. In Stage 2, multimodal large language models automatically generate detailed affective descriptions according to our well-designed chain-of-thought prompting for only a small subset of VA samples; these rich textual semantics are then injected by aligning their corresponding embeddings with VA representations through dual-path contrastive learning, further bridging the emotion gap. Extensive experiments on multiple downstream AVER benchmarks show that VAEmo achieves state-of-the-art performance with a compact design, highlighting the benefit of unified cross-modal encoding and emotion-aware semantic guidance for efficient, generalizable VA emotion representations.

[Arxiv](https://arxiv.org/abs/2505.02331)