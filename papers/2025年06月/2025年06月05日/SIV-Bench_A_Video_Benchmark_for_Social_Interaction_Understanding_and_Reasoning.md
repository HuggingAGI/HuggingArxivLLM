# SIV-Bench：用于社交互动理解和推理的视频基准测试

发布时间：2025年06月05日

`LLM应用` `社会智能` `基准测试`

> SIV-Bench: A Video Benchmark for Social Interaction Understanding and Reasoning

# 摘要

> 人类社会互动的丰富性和多方面性，包括多模态线索、不可见的关系和心理状态以及动态行为，对人工智能构成了巨大挑战。为推动这一领域的研究，我们推出了SIV-Bench，这是一个全新的视频基准测试，旨在全面评估多模态大语言模型（MLLMs）在社会场景理解（SSU）、社会状态推理（SSR）和社会动态预测（SDP）方面的能力。

SIV-Bench包含2,792个视频片段和8,792对精心设计的问题-答案，这些内容通过人与LLM协作生成。数据集源自TikTok和YouTube，涵盖广泛的视频类型、展示风格以及语言和文化背景。它还特别设计了一个场景，用于分析不同文本线索（原始屏幕文本、添加的对话或无文本）的影响。

我们在领先MLLM上的全面实验表明，尽管模型在SSU方面表现出色，但它们在SSR和SDP方面面临巨大挑战，其中关系推理（RI）是一个关键瓶颈。我们的研究还证实了转录对话在帮助理解复杂社会互动中的关键作用。通过系统性地识别当前MLLM的能力和局限性，SIV-Bench为开发更具社交智能的AI提供了重要见解。数据集和代码可在https://kfq20.github.io/sivbench/获取。

> The rich and multifaceted nature of human social interaction, encompassing multimodal cues, unobservable relations and mental states, and dynamical behavior, presents a formidable challenge for artificial intelligence. To advance research in this area, we introduce SIV-Bench, a novel video benchmark for rigorously evaluating the capabilities of Multimodal Large Language Models (MLLMs) across Social Scene Understanding (SSU), Social State Reasoning (SSR), and Social Dynamics Prediction (SDP). SIV-Bench features 2,792 video clips and 8,792 meticulously generated question-answer pairs derived from a human-LLM collaborative pipeline. It is originally collected from TikTok and YouTube, covering a wide range of video genres, presentation styles, and linguistic and cultural backgrounds. It also includes a dedicated setup for analyzing the impact of different textual cues-original on-screen text, added dialogue, or no text. Our comprehensive experiments on leading MLLMs reveal that while models adeptly handle SSU, they significantly struggle with SSR and SDP, where Relation Inference (RI) is an acute bottleneck, as further examined in our analysis. Our study also confirms the critical role of transcribed dialogue in aiding comprehension of complex social interactions. By systematically identifying current MLLMs' strengths and limitations, SIV-Bench offers crucial insights to steer the development of more socially intelligent AI. The dataset and code are available at https://kfq20.github.io/sivbench/.

[Arxiv](https://arxiv.org/abs/2506.05425)