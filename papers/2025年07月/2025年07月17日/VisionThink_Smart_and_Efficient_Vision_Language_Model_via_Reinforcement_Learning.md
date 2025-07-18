# VisionThink：借助强化学习打造的智能高效视觉语言模型

发布时间：2025年07月17日

`其他` `计算机视觉`

> VisionThink: Smart and Efficient Vision Language Model via Reinforcement Learning

# 摘要

> 视觉语言模型（VLMs）近期的突破性进展通过增加视觉标记数量显著提升了性能，但这些视觉标记往往远长于文本标记。然而，我们发现现实中大多数场景并不需要如此庞大的视觉标记数量。尽管在一小部分OCR相关任务中性能显著下降，但模型仍能在1/4分辨率下准确完成大多数其他通用VQA任务。因此，我们提出了一种动态处理不同分辨率样本的新方法，并推出了名为VisionThink的视觉标记压缩新范式。VisionThink从下采样图像开始，智能判断当前分辨率是否足以解决问题。若不足够，模型可输出特殊标记请求更高分辨率图像。与现有基于固定剪枝比例或阈值压缩标记的高效VLM方法不同，VisionThink可根据具体案例自主决定是否压缩标记。因此，它在OCR相关任务中展现了强大的细粒度视觉理解能力，同时在较简单任务中大幅节省了视觉标记。我们采用强化学习并提出LLM作为评估者的创新策略，成功将RL应用于通用VQA任务。此外，我们精心设计了奖励函数和惩罚机制，以实现稳定且合理的图像缩放调用比率。大量实验结果表明，我们的方法在性能、效率和效果上均具有显著优势。我们的代码可在GitHub仓库https://github.com/dvlab-research/VisionThink获取。
    

> Recent advancements in vision-language models (VLMs) have improved performance by increasing the number of visual tokens, which are often significantly longer than text tokens. However, we observe that most real-world scenarios do not require such an extensive number of visual tokens. While the performance drops significantly in a small subset of OCR-related tasks, models still perform accurately in most other general VQA tasks with only 1/4 resolution. Therefore, we propose to dynamically process distinct samples with different resolutions, and present a new paradigm for visual token compression, namely, VisionThink. It starts with a downsampled image and smartly decides whether it is sufficient for problem solving. Otherwise, the model could output a special token to request the higher-resolution image. Compared to existing Efficient VLM methods that compress tokens using fixed pruning ratios or thresholds, VisionThink autonomously decides whether to compress tokens case by case. As a result, it demonstrates strong fine-grained visual understanding capability on OCR-related tasks, and meanwhile saves substantial visual tokens on simpler tasks. We adopt reinforcement learning and propose the LLM-as-Judge strategy to successfully apply RL to general VQA tasks. Moreover, we carefully design a reward function and penalty mechanism to achieve a stable and reasonable image resize call ratio. Extensive experiments demonstrate the superiority, efficiency, and effectiveness of our method. Our code is available at https://github.com/dvlab-research/VisionThink.

[Arxiv](https://arxiv.org/abs/2507.13348)