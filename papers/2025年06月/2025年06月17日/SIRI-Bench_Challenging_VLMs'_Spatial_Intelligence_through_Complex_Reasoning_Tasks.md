# SIRI-Bench：通过复杂推理任务考验视觉语言模型的空间智能

发布时间：2025年06月17日

`LLM应用` `视觉语言模型` `视频分析`

> SIRI-Bench: Challenging VLMs' Spatial Intelligence through Complex Reasoning Tasks

# 摘要

> 大型语言模型（LLMs）在复杂推理领域取得了飞速进展，尤其在数学和编程方面表现突出。然而，尽管空间智能对视觉语言模型（VLMs）在现实交互中至关重要，但系统性评估其空间场景下复杂推理能力的研究仍较少。为此，我们推出了SIRI-Bench，一个通过视频推理任务评估VLMs空间智能的基准。SIRI-Bench包含近1000个视频-问题-答案三元组，每个问题均嵌入到现实的3D场景并通过视频呈现。通过精心设计问题及其3D场景，我们的基准确保了解决问题需要结合空间理解提取信息和高级推理推导答案，使其成为极具挑战性的VLMs评估基准。为实现大规模数据合成，我们开发了自动场景生成引擎，该引擎借助多个专业大型语言模型代理，能从抽象数学问题生成符合原始描述的现实3D场景。实验结果表明，目前最先进的VLMs在SIRI-Bench上表现挣扎，凸显了空间推理的挑战。我们希望本研究能引起研究者对空间推理的重视，并推动VLMs在视觉问题解决方面的发展。

> Large Language Models (LLMs) are experiencing rapid advancements in complex reasoning, exhibiting remarkable generalization in mathematics and programming. In contrast, while spatial intelligence is fundamental for Vision-Language Models (VLMs) in real-world interaction, the systematic evaluation of their complex reasoning ability within spatial contexts remains underexplored. To bridge this gap, we introduce SIRI-Bench, a benchmark designed to evaluate VLMs' spatial intelligence through video-based reasoning tasks. SIRI-Bench comprises nearly 1K video-question-answer triplets, where each problem is embedded in a realistic 3D scene and captured by video. By carefully designing questions and corresponding 3D scenes, our benchmark ensures that solving the questions requires both spatial comprehension for extracting information and high-level reasoning for deriving solutions, making it a challenging benchmark for evaluating VLMs. To facilitate large-scale data synthesis, we develop an Automatic Scene Creation Engine. This engine, leveraging multiple specialized LLM agents, can generate realistic 3D scenes from abstract math problems, ensuring faithfulness to the original descriptions. Experimental results reveal that state-of-the-art VLMs struggle significantly on SIRI-Bench, underscoring the challenge of spatial reasoning. We hope that our study will bring researchers' attention to spatially grounded reasoning and advance VLMs in visual problem-solving.

[Arxiv](https://arxiv.org/abs/2506.14512)