# # 连接手语与口语：手语翻译中的伪口译生成

发布时间：2025年05月21日

`LLM应用` `手语翻译` `计算机视觉`

> Bridging Sign and Spoken Languages: Pseudo Gloss Generation for Sign Language Translation

# 摘要

> 手语翻译的目标是将手语视频转化为口语文本。传统方法依赖于手语注释作为中间表示，将任务拆分为视频到手语识别和手语到文本翻译两个子任务。尽管有效，但这一方法受限于昂贵且稀缺的手语注释，难以大规模应用。为解决这一难题，我们提出了一种无需手语注释的伪注释生成框架，既避免了人工标注，又保留了中间表示的结构优势。具体而言，我们利用大型语言模型（LLM）的上下文学习能力，通过少量示例文本-手语对，从口语文本中生成初步手语注释。为了提升生成的伪注释与视频手语序列的对应关系，我们通过弱监督学习调整伪注释顺序，实现更好的对齐。这种调整不仅支持辅助对齐目标的整合，还使我们能够借助连接主义时间分类（CTC）损失实现高效监督。我们的SLT模型由视觉编码器和翻译器组成，通过三阶段管道训练，逐步缩小手语与口语之间的模态差异。尽管方法简洁，但在两个基准测试中，我们的框架不仅超越了现有无注释方法，还与基于注释的方法不相上下，展现了强大的竞争力。

> Sign Language Translation (SLT) aims to map sign language videos to spoken language text. A common approach relies on gloss annotations as an intermediate representation, decomposing SLT into two sub-tasks: video-to-gloss recognition and gloss-to-text translation. While effective, this paradigm depends on expert-annotated gloss labels, which are costly and rarely available in existing datasets, limiting its scalability. To address this challenge, we propose a gloss-free pseudo gloss generation framework that eliminates the need for human-annotated glosses while preserving the structured intermediate representation. Specifically, we prompt a Large Language Model (LLM) with a few example text-gloss pairs using in-context learning to produce draft sign glosses from spoken language text. To enhance the correspondence between LLM-generated pseudo glosses and the sign sequences in video, we correct the ordering in the pseudo glosses for better alignment via a weakly supervised learning process. This reordering facilitates the incorporation of auxiliary alignment objectives, and allows for the use of efficient supervision via a Connectionist Temporal Classification (CTC) loss. We train our SLT mode, which consists of a vision encoder and a translator, through a three-stage pipeline, which progressively narrows the modality gap between sign language and spoken language. Despite its simplicity, our approach outperforms previous state-of-the-art gloss-free frameworks on two SLT benchmarks and achieves competitive results compared to gloss-based methods.

[Arxiv](https://arxiv.org/abs/2505.15438)