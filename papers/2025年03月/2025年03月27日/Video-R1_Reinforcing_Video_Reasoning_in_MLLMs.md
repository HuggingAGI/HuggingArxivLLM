# Video-R1：在多模态大语言模型中强化视频推理能力的研究。

发布时间：2025年03月27日

`LLM应用

摘要中提到Video-R1通过强化学习来提升多模态大型语言模型的视频推理能力，属于LLM的应用场景。` `视频技术` `计算机视觉`

> Video-R1: Reinforcing Video Reasoning in MLLMs

# 摘要

> 受DeepSeek-R1通过基于规则的强化学习（RL）成功激发推理能力的启发，我们推出Video-R1，这是首个系统性探索R1范式以激发多模态大型语言模型（MLLMs）视频推理能力的尝试。然而，直接将GRPO算法应用于视频推理的强化学习训练面临两大挑战：其一，视频推理缺乏时间建模；其二，高质量视频推理数据的稀缺性。为解决这些问题，我们首先提出了T-GRPO算法，引导模型充分挖掘视频中的时间信息进行推理。此外，除了视频数据外，我们还引入了高质量的图像推理数据进行训练。我们精心构建了两个数据集：Video-R1-COT-165k用于SFT冷启动，Video-R1-260k用于RL训练，两者均包含丰富的图像和视频数据。实验结果表明，Video-R1在VideoMMMU和VSI-Bench等视频推理基准测试中表现优异，同时在MVBench和TempCompass等通用视频基准测试中也取得了显著提升。特别值得一提的是，Video-R1-7B在视频空间推理基准VSI-bench上达到了35.8%的准确率，超越了商用专有模型GPT-4o。所有代码、模型和数据均已公开发布。

> Inspired by DeepSeek-R1's success in eliciting reasoning abilities through rule-based reinforcement learning (RL), we introduce Video-R1 as the first attempt to systematically explore the R1 paradigm for eliciting video reasoning within multimodal large language models (MLLMs). However, directly applying RL training with the GRPO algorithm to video reasoning presents two primary challenges: (i) a lack of temporal modeling for video reasoning, and (ii) the scarcity of high-quality video-reasoning data. To address these issues, we first propose the T-GRPO algorithm, which encourages models to utilize temporal information in videos for reasoning. Additionally, instead of relying solely on video data, we incorporate high-quality image-reasoning data into the training process. We have constructed two datasets: Video-R1-COT-165k for SFT cold start and Video-R1-260k for RL training, both comprising image and video data. Experimental results demonstrate that Video-R1 achieves significant improvements on video reasoning benchmarks such as VideoMMMU and VSI-Bench, as well as on general video benchmarks including MVBench and TempCompass, etc. Notably, Video-R1-7B attains a 35.8% accuracy on video spatial reasoning benchmark VSI-bench, surpassing the commercial proprietary model GPT-4o. All codes, models, data are released.

[Arxiv](https://arxiv.org/abs/2503.21776)