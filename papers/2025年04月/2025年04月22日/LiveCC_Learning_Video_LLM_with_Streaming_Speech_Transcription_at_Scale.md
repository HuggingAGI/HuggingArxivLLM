# LiveCC：通过大规模实时语音转写学习视频大语言模型

发布时间：2025年04月22日

`LLM应用` `视频处理`

> LiveCC: Learning Video LLM with Streaming Speech Transcription at Scale

# 摘要

> 最近的视频大型语言模型（Video LLMs）通常依赖昂贵的人工标注或专有模型API（如GPT-4o）生成训练数据，这限制了其在大规模训练中的应用。本文提出了一种基于廉价自动语音识别（ASR）转录的视频LLM大规模训练方法。我们创新性地提出了一种流式训练方法，根据时间戳密集交错ASR词汇和视频帧。与现有基于ASR的视觉语言建模研究相比，我们的方法更贴合ASR的流式特性，使模型能够学习时间对齐的细粒度视觉语言建模。为支持这一训练算法，我们构建了一个数据生产管道，处理YouTube视频及其字幕（CC，与ASR相同），生成了用于预训练的Live-CC-5M数据集和用于高质量监督微调（SFT）的Live-WhisperX-526K数据集。值得注意的是，即使不进行SFT，仅基于ASR预训练的LiveCC-7B-Base模型在通用视频问答任务中也表现出色，并在实时视频评论中展现出新能力。为此，我们精心设计了新的LiveSports-3K基准测试，使用LLM作为评估器来衡量自由形式评论的质量。实验结果表明，我们的最终LiveCC-7B-Instruct模型即使在实时模式下，其评论质量也能超越先进的72B模型（如Qwen2.5-VL-72B-Instruct和LLaVA-Video-72B），同时在VideoMME和OVOBench等流行视频问答基准测试中实现了7B/8B规模下的最先进结果，充分展现了我们方法的广泛适用性。本文的所有资源均可在https://showlab.github.io/livecc获取。

> Recent video large language models (Video LLMs) often depend on costly human annotations or proprietary model APIs (e.g., GPT-4o) to produce training data, which limits their training at scale. In this paper, we explore large-scale training for Video LLM with cheap automatic speech recognition (ASR) transcripts. Specifically, we propose a novel streaming training approach that densely interleaves the ASR words and video frames according to their timestamps. Compared to previous studies in vision-language representation with ASR, our method naturally fits the streaming characteristics of ASR, thus enabling the model to learn temporally-aligned, fine-grained vision-language modeling. To support the training algorithm, we introduce a data production pipeline to process YouTube videos and their closed captions (CC, same as ASR), resulting in Live-CC-5M dataset for pre-training and Live-WhisperX-526K dataset for high-quality supervised fine-tuning (SFT). Remarkably, even without SFT, the ASR-only pre-trained LiveCC-7B-Base model demonstrates competitive general video QA performance and exhibits a new capability in real-time video commentary. To evaluate this, we carefully design a new LiveSports-3K benchmark, using LLM-as-a-judge to measure the free-form commentary. Experiments show our final LiveCC-7B-Instruct model can surpass advanced 72B models (Qwen2.5-VL-72B-Instruct, LLaVA-Video-72B) in commentary quality even working in a real-time mode. Meanwhile, it achieves state-of-the-art results at the 7B/8B scale on popular video QA benchmarks such as VideoMME and OVOBench, demonstrating the broad generalizability of our approach. All resources of this paper have been released at https://showlab.github.io/livecc.

[Arxiv](https://arxiv.org/abs/2504.16030)