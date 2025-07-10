# 无字幕手语翻译的层次特征对齐

发布时间：2025年07月09日

`LLM应用

摘要中提到大型语言模型（LLMs）的最新进展使GLOSS-free SLT成为可能，并提出了一种结合伪GLOSS和对比视频-语言对齐的新方法，以提升翻译质量。这表明论文主要探讨了LLMs在手语翻译中的实际应用，属于LLM应用类别。` `手语翻译` `视频处理`

> Hierarchical Feature Alignment for Gloss-Free Sign Language Translation

# 摘要

> # 手语翻译
手语翻译（SLT）致力于将手语视频转化为口语句子。现有方法在端到端学习过程中往往难以克服视觉与文本表示之间的差距。GLOSS方法通过利用结构化的语言信息，有助于缩小这一差距。而GLOSS-free方法则提供了更大的灵活性，并去除了标注的负担，但需要有效的对齐策略。大型语言模型（LLMs）的最新进展使GLOSS-free SLT成为可能，通过从手语视频生成文本类表示。本文提出了一种受手语结构启发的新型层次预训练策略，结合伪GLOSS和对比视频-语言对齐。我们的方法分层次提取帧、片段和视频级别的特征，并与伪GLOSS和口语句子对齐，以提升翻译质量。实验表明，我们的方法在保持效率的同时，能够提高BLEU-4和ROUGE分数。

> Sign Language Translation (SLT) attempts to convert sign language videos into spoken sentences. However, many existing methods struggle with the disparity between visual and textual representations during end-to-end learning. Gloss-based approaches help to bridge this gap by leveraging structured linguistic information. While, gloss-free methods offer greater flexibility and remove the burden of annotation, they require effective alignment strategies. Recent advances in Large Language Models (LLMs) have enabled gloss-free SLT by generating text-like representations from sign videos. In this work, we introduce a novel hierarchical pre-training strategy inspired by the structure of sign language, incorporating pseudo-glosses and contrastive video-language alignment. Our method hierarchically extracts features at frame, segment, and video levels, aligning them with pseudo-glosses and the spoken sentence to enhance translation quality. Experiments demonstrate that our approach improves BLEU-4 and ROUGE scores while maintaining efficiency.

[Arxiv](https://arxiv.org/abs/2507.06732)