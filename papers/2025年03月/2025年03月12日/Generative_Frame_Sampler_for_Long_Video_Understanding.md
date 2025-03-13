# 长视频理解的生成式帧采样器

发布时间：2025年03月12日

`LLM应用` `视频处理` `人工智能`

> Generative Frame Sampler for Long Video Understanding

# 摘要

> 尽管视频大型语言模型（VideoLLMs）近期取得了进展，但有效理解长视频仍然是一个重大挑战。处理包含数千帧的长视频会带来巨大的计算负担。为了解决这一问题，本文提出了生成式帧采样器（GenS），这是一个与VideoLLMs集成的即插即用模块，旨在促进对长视频的高效感知。GenS基于轻量级VideoLLM构建，利用其固有的视觉-语言能力来识别与问题相关的帧。为了促进有效的检索，我们构建了GenS-Video-150K，这是一个大规模的视频指令数据集，包含密集的帧相关性标注。大量实验表明，GenS始终能够提升各种VideoLLMs的性能，包括开源模型（Qwen2-VL-7B、Aria-25B、VILA-40B、LLaVA-Video-7B/72B）和专有助手（GPT-4o、Gemini）。配备GenS后，开源VideoLLMs在长视频基准测试中实现了令人印象深刻的最新结果：LLaVA-Video-72B在LongVideoBench上达到66.8（+4.3），在MLVU上达到77.0（+2.7），而Aria在HourVideo上获得了39.2分，超过了Gemini-1.5-pro 1.9分。我们将在https://generative-sampler.github.io上发布所有数据集和模型。

> Despite recent advances in Video Large Language Models (VideoLLMs), effectively understanding long-form videos remains a significant challenge. Perceiving lengthy videos containing thousands of frames poses substantial computational burden. To mitigate this issue, this paper introduces Generative Frame Sampler (GenS), a plug-and-play module integrated with VideoLLMs to facilitate efficient lengthy video perception. Built upon a lightweight VideoLLM, GenS leverages its inherent vision-language capabilities to identify question-relevant frames. To facilitate effective retrieval, we construct GenS-Video-150K, a large-scale video instruction dataset with dense frame relevance annotations. Extensive experiments demonstrate that GenS consistently boosts the performance of various VideoLLMs, including open-source models (Qwen2-VL-7B, Aria-25B, VILA-40B, LLaVA-Video-7B/72B) and proprietary assistants (GPT-4o, Gemini). When equipped with GenS, open-source VideoLLMs achieve impressive state-of-the-art results on long-form video benchmarks: LLaVA-Video-72B reaches 66.8 (+4.3) on LongVideoBench and 77.0 (+2.7) on MLVU, while Aria obtains 39.2 on HourVideo surpassing the Gemini-1.5-pro by 1.9 points. We will release all datasets and models at https://generative-sampler.github.io.

[Arxiv](https://arxiv.org/abs/2503.09146)