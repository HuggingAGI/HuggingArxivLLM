# Audio Flamingo 2: 具备长音频理解与专家推理能力的音频-语言模型

发布时间：2025年03月05日

`LLM应用

理由：这篇论文主要介绍了一种具备音频理解和推理能力的音频语言模型（Audio Flamingo 2），并展示了其在长音频处理方面的应用和性能提升。论文的重点在于模型的应用和具体任务的实现，属于LLM应用领域。` `音频处理` `多模态模型`

> Audio Flamingo 2: An Audio-Language Model with Long-Audio Understanding and Expert Reasoning Abilities

# 摘要

> 理解并推理非语音声音和音乐，对于人类和AI代理与环境的交互至关重要。本文介绍了一款具备先进音频理解和推理能力的音频语言模型——Audio Flamingo 2 (AF2)。AF2通过(i)定制的CLAP模型，(ii)用于细粒度音频推理的合成问答数据，以及(iii)多阶段课程学习策略，实现了卓越性能。值得注意的是，AF2仅使用30亿参数的小型语言模型，便在超过20个基准测试中超越了众多大型开源和专有模型。

此外，我们首次将音频理解扩展至长音频片段（30秒至5分钟），并推出大规模新颖数据集LongAudio，用于训练ALM在长音频描述和问答任务上的能力。在LongAudio上对AF2进行微调后，其在LongAudioBench（一个评估ALM长音频理解能力的专家标注基准测试）中表现优异。通过广泛的消融研究，我们进一步验证了方法的有效性。项目详情请访问：https://research.nvidia.com/labs/adlr/AF2/.

> Understanding and reasoning over non-speech sounds and music are crucial for both humans and AI agents to interact effectively with their environments. In this paper, we introduce Audio Flamingo 2 (AF2), an Audio-Language Model (ALM) with advanced audio understanding and reasoning capabilities. AF2 leverages (i) a custom CLAP model, (ii) synthetic Audio QA data for fine-grained audio reasoning, and (iii) a multi-stage curriculum learning strategy. AF2 achieves state-of-the-art performance with only a 3B parameter small language model, surpassing large open-source and proprietary models across over 20 benchmarks. Next, for the first time, we extend audio understanding to long audio segments (30 secs to 5 mins) and propose LongAudio, a large and novel dataset for training ALMs on long audio captioning and question-answering tasks. Fine-tuning AF2 on LongAudio leads to exceptional performance on our proposed LongAudioBench, an expert annotated benchmark for evaluating ALMs on long audio understanding capabilities. We conduct extensive ablation studies to confirm the efficacy of our approach. Project Website: https://research.nvidia.com/labs/adlr/AF2/.

[Arxiv](https://arxiv.org/abs/2503.03983)