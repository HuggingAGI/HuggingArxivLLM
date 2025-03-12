# # 视频动作差分

发布时间：2025年03月10日

`Agent` `视频分析`

> Video Action Differencing

# 摘要

> 当两个人执行相同动作时，他们之间存在哪些差异？本研究引入了 Video Action Differencing (VidDiff)，一个识别同一动作视频之间细微差异的新颖任务，具有广泛的应用前景，例如教练和技能学习。为了推动这一新任务的发展，我们构建了 VidDiffBench，一个包含 549 个视频对的基准数据集，附带了 4,469 个细粒度动作差异的人工标注以及 2,075 个定位时间戳，用于指示这些差异发生的位置。实验表明，VidDiffBench 对当前最先进的大语言多模态模型（如 GPT-4o 和 Qwen2-VL）提出了严峻的挑战。通过分析这些模型在 VidDiffBench 上的失败案例，我们指出了两大关键挑战：在两个视频中定位相关子动作以及进行细粒度帧比较。为了解决这些问题，我们提出了 VidDiff 方法，这是一种基于智能体的工作流，将任务分解为三个阶段：动作差异提案、关键帧定位和帧差异比较，每个阶段均采用了专门的基础模型。为了鼓励未来在这一新任务上的研究，我们发布了基准数据集（https://huggingface.co/datasets/jmhb/VidDiffBench）和代码（http://jmhb0.github.io/viddiff）。

> How do two individuals differ when performing the same action? In this work, we introduce Video Action Differencing (VidDiff), the novel task of identifying subtle differences between videos of the same action, which has many applications, such as coaching and skill learning. To enable development on this new task, we first create VidDiffBench, a benchmark dataset containing 549 video pairs, with human annotations of 4,469 fine-grained action differences and 2,075 localization timestamps indicating where these differences occur. Our experiments demonstrate that VidDiffBench poses a significant challenge for state-of-the-art large multimodal models (LMMs), such as GPT-4o and Qwen2-VL. By analyzing failure cases of LMMs on VidDiffBench, we highlight two key challenges for this task: localizing relevant sub-actions over two videos and fine-grained frame comparison. To overcome these, we propose the VidDiff method, an agentic workflow that breaks the task into three stages: action difference proposal, keyframe localization, and frame differencing, each stage utilizing specialized foundation models. To encourage future research in this new task, we release the benchmark at https://huggingface.co/datasets/jmhb/VidDiffBench and code at http://jmhb0.github.io/viddiff.

[Arxiv](https://arxiv.org/abs/2503.07860)