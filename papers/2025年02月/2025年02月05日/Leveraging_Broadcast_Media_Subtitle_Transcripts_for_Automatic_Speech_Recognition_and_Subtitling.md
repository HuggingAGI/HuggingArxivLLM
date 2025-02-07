# 利用广播媒体字幕转录实现自动语音识别与字幕生成

发布时间：2025年02月05日

`其他

理由：这篇论文主要讨论的是语音识别技术（ASR）的改进，特别是针对低资源语言和方言的挑战。虽然提到了大规模数据集和基于注意力机制的架构，但这些内容并不直接涉及大型语言模型（LLM）的应用、理论、RAG（Retrieval-Augmented Generation）或Agent（智能体）技术。因此，这篇论文更适合归类为“其他”。` `语音识别` `字幕生成`

> Leveraging Broadcast Media Subtitle Transcripts for Automatic Speech Recognition and Subtitling

# 摘要

> # 摘要
近年来，语音识别技术的进步主要得益于大规模数据集和基于注意力机制的架构，但低资源语言和方言仍面临诸多挑战。本文探讨了将电视字幕中的弱监督转录集成到自动语音识别（ASR）系统中的方法，旨在提升逐字转录和自动生成字幕的质量。由于逐字数据和字幕的特性不同，我们将其视为不同的领域或语言。我们提出并比较了几种端到端架构，这些架构通过独立或共享的编码器和解码器联合建模两种模态，能够同时生成逐字转录和字幕。在佛兰芒语（比利时荷兰语）上的评估表明，采用级联编码器和独立解码器的模型能够高效捕捉两种数据类型的差异，并在两个领域均取得改进。尽管领域和语言变体存在差异，结合逐字转录与字幕数据显著提升了ASR性能，且无需大量预处理。此外，大规模字幕数据集的实验验证了该方法的可扩展性。这些方法不仅提高了ASR准确性，还生成了与标准书面文本高度一致的字幕，具有广泛的应用潜力。

> The recent advancement of speech recognition technology has been driven by large-scale datasets and attention-based architectures, but many challenges still remain, especially for low-resource languages and dialects. This paper explores the integration of weakly supervised transcripts from TV subtitles into automatic speech recognition (ASR) systems, aiming to improve both verbatim transcriptions and automatically generated subtitles. To this end, verbatim data and subtitles are regarded as different domains or languages, due to their distinct characteristics. We propose and compare several end-to-end architectures that are designed to jointly model both modalities with separate or shared encoders and decoders. The proposed methods are able to jointly generate a verbatim transcription and a subtitle. Evaluation on Flemish (Belgian Dutch) demonstrates that a model with cascaded encoders and separate decoders allows to represent the differences between the two data types most efficiently while improving on both domains. Despite differences in domain and linguistic variations, combining verbatim transcripts with subtitle data leads to notable ASR improvements without the need for extensive preprocessing. Additionally, experiments with a large-scale subtitle dataset show the scalability of the proposed approach. The methods not only improve ASR accuracy but also generate subtitles that closely match standard written text, offering several potential applications.

[Arxiv](https://arxiv.org/abs/2502.03212)