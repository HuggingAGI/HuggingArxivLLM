# # 3DAxisPrompt: 提升GPT-4o中的三维空间理解和推理能力

发布时间：2025年03月17日

`LLM应用` `三维视觉` `计算机视觉`

> 3DAxisPrompt: Promoting the 3D Grounding and Reasoning in GPT-4o

# 摘要

> 多模态大型语言模型（MLLMs）在多种任务中展现出了令人瞩目的能力，尤其是在配备了精心设计的视觉提示时表现尤为出色。然而，现有研究主要集中在逻辑推理和视觉理解方面，而MLLMs在三维视觉任务中的实际应用能力仍是一个值得探索的领域。本文中，我们提出了一种名为3DAxisPrompt的新颖视觉提示方法，旨在激发MLLMs在真实场景中的三维理解能力。具体而言，我们的方法利用三维坐标轴和Segment Anything Model（SAM）生成的掩膜，为MLLMs提供明确的几何先验，进而将它们在二维场景中出色的定位和推理能力扩展到真实世界的三维场景中。此外，我们首次对潜在的视觉提示格式进行了全面研究，并总结了我们的发现，揭示了GPT-4o（作为MLLMs的代表）在三维理解能力方面的潜力和局限性。最后，我们构建了包含四个数据集（即ScanRefer、ScanNet、FMB和nuScene数据集）的评估环境，涵盖了各种三维任务。基于此，我们进行了广泛的定量和定性实验，结果证明了所提出方法的有效性。总体而言，我们的研究表明，在3DAxisPrompt的帮助下，MLLMs能够有效感知真实场景中物体的三维位置。然而，单一的提示工程方法并不能在所有三维任务中始终取得最佳效果。这项研究强调了利用提示工程技术将MLLMs应用于三维视觉定位/推理任务的可行性。

> Multimodal Large Language Models (MLLMs) exhibit impressive capabilities across a variety of tasks, especially when equipped with carefully designed visual prompts. However, existing studies primarily focus on logical reasoning and visual understanding, while the capability of MLLMs to operate effectively in 3D vision remains an ongoing area of exploration. In this paper, we introduce a novel visual prompting method, called 3DAxisPrompt, to elicit the 3D understanding capabilities of MLLMs in real-world scenes. More specifically, our method leverages the 3D coordinate axis and masks generated from the Segment Anything Model (SAM) to provide explicit geometric priors to MLLMs and then extend their impressive 2D grounding and reasoning ability to real-world 3D scenarios. Besides, we first provide a thorough investigation of the potential visual prompting formats and conclude our findings to reveal the potential and limits of 3D understanding capabilities in GPT-4o, as a representative of MLLMs. Finally, we build evaluation environments with four datasets, i.e., ScanRefer, ScanNet, FMB, and nuScene datasets, covering various 3D tasks. Based on this, we conduct extensive quantitative and qualitative experiments, which demonstrate the effectiveness of the proposed method. Overall, our study reveals that MLLMs, with the help of 3DAxisPrompt, can effectively perceive an object's 3D position in real-world scenarios. Nevertheless, a single prompt engineering approach does not consistently achieve the best outcomes for all 3D tasks. This study highlights the feasibility of leveraging MLLMs for 3D vision grounding/reasoning with prompt engineering techniques.

[Arxiv](https://arxiv.org/abs/2503.13185)