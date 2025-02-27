# M2-omni：提升 Omni-MLLM，支持全面模态并具备竞争力性能

发布时间：2025年02月25日

`LLM理论` `人工智能`

> M2-omni: Advancing Omni-MLLM for Comprehensive Modality Support with Competitive Performance

# 摘要

> 我们很高兴推出M2-omni——一款前沿的开源全模态大语言模型，其性能可与GPT-4o相媲美。M2-omni采用了统一的多模态序列建模框架，赋予大型语言模型跨模态理解与生成的综合能力。它能够处理任意组合的音频、视频、图像和文本输入，并生成交织着多种模态输出的序列，从而带来先进且互动式的实时体验。然而，训练全模态大语言模型面临跨模态数据量和收敛速率的巨大差异。为解决这一问题，我们在预训练阶段采用了步平衡策略来处理数据量差异，并在指令微调阶段引入了动态自适应平衡策略，以同步模态训练进度，确保最优收敛。值得注意的是，我们在整个训练过程中始终重视保持模型在纯文本任务中的强劲性能，以维持其语言理解能力的稳健性。M2-omni凭借其全面的模态与任务支持以及卓越的性能表现，目前是一个极具竞争力的开源模型。我们相信，M2-omni将推动全模态大语言模型的发展，从而为该领域的未来研究提供助力。

> We present M2-omni, a cutting-edge, open-source omni-MLLM that achieves competitive performance to GPT-4o. M2-omni employs a unified multimodal sequence modeling framework, which empowers Large Language Models(LLMs) to acquire comprehensive cross-modal understanding and generation capabilities. Specifically, M2-omni can process arbitrary combinations of audio, video, image, and text modalities as input, generating multimodal sequences interleaving with audio, image, or text outputs, thereby enabling an advanced and interactive real-time experience. The training of such an omni-MLLM is challenged by significant disparities in data quantity and convergence rates across modalities. To address these challenges, we propose a step balance strategy during pre-training to handle the quantity disparities in modality-specific data. Additionally, a dynamically adaptive balance strategy is introduced during the instruction tuning stage to synchronize the modality-wise training progress, ensuring optimal convergence. Notably, we prioritize preserving strong performance on pure text tasks to maintain the robustness of M2-omni's language understanding capability throughout the training process. To our best knowledge, M2-omni is currently a very competitive open-source model to GPT-4o, characterized by its comprehensive modality and task support, as well as its exceptional performance. We expect M2-omni will advance the development of omni-MLLMs, thus facilitating future research in this domain.

[Arxiv](https://arxiv.org/abs/2502.18778)