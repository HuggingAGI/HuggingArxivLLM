# 评估零样本TTS的韵律多样性：新指标、基准与探索

发布时间：2025年09月24日

`其他` `媒体与娱乐`

> Measuring Prosody Diversity in Zero-Shot TTS: A New Metric, Benchmark, and Exploration

# 摘要

> 韵律多样性是实现零样本文本到语音（TTS）自然度与表现力的核心要素。然而，常用的声学指标仅能反映韵律变化的局部特征，且与人类感知的相关性较弱，使得韵律多样性的可靠量化问题尚未得到充分研究。为此，我们构建了ProsodyEval——一个韵律多样性评估数据集，该数据集除传统声学指标外，还提供了韵律平均意见分（PMOS）。该数据集包含来自7个主流TTS系统的1000条语音样本，并附有2000条人工评分。基于此，我们提出离散化语音加权编辑距离（DS-WED）这一新的客观多样性指标，通过语义标记的加权编辑距离来量化韵律变化。在ProsodyEval上的实验结果显示，DS-WED与人类主观评价的相关性显著优于现有声学指标，且在HuBERT和WavLM的语音标记化过程中表现出极强的稳健性。借助DS-WED，我们在LibriSpeech test-clean和Seed-TTS test-en数据集上对当前主流开源TTS系统进行了性能基准测试，并通过深入分析发现了影响韵律多样性的多个关键因素，如生成建模范式、时长控制机制及强化学习方法。此外，研究还发现，当前大型音频语言模型（LALMs）对韵律变化的捕捉能力仍存在局限。相关音频样本可访问https://prosodyeval.github.io获取。

> Prosody diversity is essential for achieving naturalness and expressiveness in zero-shot text-to-speech (TTS). However, frequently used acoustic metrics capture only partial views of prosodic variation and correlate poorly with human perception, leaving the problem of reliably quantifying prosody diversity underexplored. To bridge this gap, we introduce ProsodyEval, a prosody diversity assessment dataset that provides Prosody Mean Opinion Score (PMOS) alongside conventional acoustic metrics. ProsodyEval comprises 1000 speech samples derived from 7 mainstream TTS systems, with 2000 human ratings. Building on this, we propose the Discretized Speech Weighted Edit Distance (DS-WED), a new objective diversity metric that quantifies prosodic variation via weighted edit distance over semantic tokens. Experiments on ProsodyEval show that DS-WED achieves substantially higher correlation with human judgments than existing acoustic metrics, while remaining highly robust in speech tokenization from HuBERT and WavLM. Leveraging DS-WED, we benchmark state-of-the-art open-source TTS systems on LibriSpeech test-clean and Seed-TTS test-en, and further explorations uncover several factors that influence prosody diversity, including generative modeling paradigms, duration control, and reinforcement learning. Moreover, we find that current large audio language models (LALMs) remain limited in capturing prosodic variations. Audio samples are available at https://prosodyeval.github.io.

[Arxiv](https://arxiv.org/abs/2509.19928)