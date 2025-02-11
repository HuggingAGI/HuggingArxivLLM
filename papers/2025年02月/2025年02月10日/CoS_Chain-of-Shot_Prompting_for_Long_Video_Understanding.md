# CoS: 链式提示助力长视频内容的深入理解

发布时间：2025年02月10日

`LLM应用` `视频处理` `计算机视觉`

> CoS: Chain-of-Shot Prompting for Long Video Understanding

# 摘要

> 多模态大语言模型（MLLMs）在处理长视频时面临挑战，主要是因为需要大量视觉标记。这些标记远远超出了 MLLMs 的上下文长度限制，导致视频中充斥着大量与任务无关的冗余镜头。如何选择镜头成为一个亟待解决的关键问题：稀疏采样可能遗漏重要细节，而全面采样则会用无关内容淹没模型，导致视频理解出错。为了解决这一问题，我们提出了镜头链提示法（CoS）。其核心思想是将镜头选择视为测试时的视觉提示优化问题，通过优化镜头与任务的对齐，自适应地选择有助于视频语义理解的镜头。CoS 包含两个关键部分：(1) 一种二进制视频摘要机制，执行伪时间定位，发现一种二进制编码以识别与任务相关的镜头；(2) 一个视频协同推理模块，利用二进制编码将与任务相关的正样本镜头与无关的负样本镜头进行配对（学习对齐），从而优化视频理解。通过将优化后的镜头选择嵌入原始视频，CoS 能够聚焦于相关上下文，从而提升长视频理解效果。在三个基线模型和五个数据集上的实验结果验证了 CoS 的有效性和适应性。代码可参考 https://lwpyh.github.io/CoS。

> Multi-modal Large Language Models (MLLMs) struggle with long videos due to the need for excessive visual tokens. These tokens exceed massively the context length of MLLMs, resulting in filled by redundant task-irrelevant shots. How to select shots is an unsolved critical problem: sparse sampling risks missing key details, while exhaustive sampling overwhelms the model with irrelevant content, leading to video misunderstanding. To solve this problem, we propose Chain-of-Shot prompting (CoS). The key idea is to frame shot selection as test-time visual prompt optimisation, choosing shots adaptive to video understanding semantic task by optimising shots-task alignment. CoS has two key parts: (1) a binary video summary mechanism that performs pseudo temporal grounding, discovering a binary coding to identify task-relevant shots, and (2) a video co-reasoning module that deploys the binary coding to pair (learning to align) task-relevant positive shots with irrelevant negative shots. It embeds the optimised shot selections into the original video, facilitating a focus on relevant context to optimize long video understanding. Experiments across three baselines and five datasets demonstrate the effectiveness and adaptability of CoS. Code given in https://lwpyh.github.io/CoS.

[Arxiv](https://arxiv.org/abs/2502.06428)