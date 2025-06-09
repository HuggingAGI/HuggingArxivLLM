# VideoChat-A1：探索长视频理解新思路——镜头链推理方法

发布时间：2025年06月06日

`LLM应用` `视频理解` `问答系统`

> VideoChat-A1: Thinking with Long Videos by Chain-of-Shot Reasoning

# 摘要

> # 摘要  
近期在视频理解领域取得的进展主要得益于多模态大型语言模型（MLLMs）。然而，这些MLLMs擅长分析短视频，但在理解具有较长上下文的视频时却面临困难。为了解决这一难题，最近提出了一些基于MLLMs作为代理来检索长视频中额外上下文知识的代理范式。然而，现有大多数代理忽略了长视频由多个镜头组成这一关键事实，即要从长视频中回答用户问题，必须像人类一样深入理解与问题相关的镜头。由于缺乏这种见解，这些代理常常错误地检索冗余甚至噪声时间上下文，限制了它们对长视频的理解能力。为填补这一空白，我们提出了VideoChat-A1，一种全新的长视频代理范式。与以往工作不同，我们的VideoChat-A1能够通过独特的镜头链推理范式深入思考长视频。具体而言，它可以逐步选择与用户问题相关的镜头，并以粗到细的方式深入分析这些镜头。通过沿着镜头链进行多模态推理，VideoChat-A1能够有效模拟人类逐步的思维过程，从而在长视频中交互式地发现更优质的时序上下文，实现深思熟虑的理解。大量实验表明，VideoChat-A1在主流长视频问答基准上达到了最先进的性能，例如在VideoMME上达到了77.0，在EgoSchema上达到了70.1，超过了其强大的基线模型（如Intern2.5VL-8B和InternVideo2.5-8B），分别高出10.8%和6.2%。与领先的闭源模型GPT-4和Gemini 1.5 Pro相比，VideoChat-A1提供了具有竞争力的准确性，同时在输入帧数和推理时间上平均减少了7%和12%。

> The recent advance in video understanding has been driven by multimodal large language models (MLLMs). But these MLLMs are good at analyzing short videos, while suffering from difficulties in understanding videos with a longer context. To address this difficulty, several agent paradigms have recently been proposed, using MLLMs as agents for retrieving extra contextual knowledge in a long video. However, most existing agents ignore the key fact that a long video is composed with multiple shots, i.e., to answer the user question from a long video, it is critical to deeply understand its relevant shots like human. Without such insight, these agents often mistakenly find redundant even noisy temporal context, restricting their capacity for long video understanding. To fill this gap, we propose VideoChat-A1, a novel long video agent paradigm. Different from the previous works, our VideoChat-A1 can deeply think with long videos, via a distinct chain-of-shot reasoning paradigm. More specifically, it can progressively select the relevant shots of user question, and look into these shots in a coarse-to-fine partition. By multi-modal reasoning along the shot chain, VideoChat-A1 can effectively mimic step-by-step human thinking process, allowing to interactively discover preferable temporal context for thoughtful understanding in long videos. Extensive experiments show that, our VideoChat-A1 achieves the state-of-the-art performance on the mainstream long video QA benchmarks, e.g., it achieves 77.0 on VideoMME and 70.1 on EgoSchema, outperforming its strong baselines (e.g., Intern2.5VL-8B and InternVideo2.5-8B), by up to 10.8\% and 6.2\%. Compared to leading close-source GPT-4o and Gemini 1.5 Pro, VideoChat-A1 offers competitive accuracy, but with 7\% input frames and 12\% inference time on average.

[Arxiv](https://arxiv.org/abs/2506.06097)