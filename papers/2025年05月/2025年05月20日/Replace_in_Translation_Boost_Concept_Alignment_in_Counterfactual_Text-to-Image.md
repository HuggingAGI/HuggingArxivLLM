# 跨语言替换：提升反事实文本到图像生成中的概念对齐

发布时间：2025年05月20日

`LLM应用` `人工智能` `计算机视觉`

> Replace in Translation: Boost Concept Alignment in Counterfactual Text-to-Image

# 摘要

> 文本到图像（T2I）近年来风靡一时，大部分常见条件任务已得到良好优化。然而，反事实文本到图像正在限制我们获得更丰富的AIGC体验。针对现实中不可能发生且违背物理定律的场景，我们应致力于增强图像的事实感——即生成人们认为非常可能发生的真实图像，并实现概念对齐——即所有所需对象应在同一画面中。本文聚焦于概念对齐问题。鉴于可控T2I模型已在实际应用中表现优异，我们利用该技术逐步替换潜在空间中合成图像的对象，将其从常见场景转换为反事实场景，以满足提示要求。我们提出了一种名为显式逻辑叙述提示（ELNP）的策略，通过最新的SoTA语言模型DeepSeek生成指令来指导这一替换过程。此外，为评估模型在反事实T2I中的性能，我们设计了一种指标来计算提示中所需概念在合成图像中平均覆盖的数量。大量实验和定性比较表明，我们的策略能够显著提升反事实T2I中的概念对齐效果。

> Text-to-Image (T2I) has been prevalent in recent years, with most common condition tasks having been optimized nicely. Besides, counterfactual Text-to-Image is obstructing us from a more versatile AIGC experience. For those scenes that are impossible to happen in real world and anti-physics, we should spare no efforts in increasing the factual feel, which means synthesizing images that people think very likely to be happening, and concept alignment, which means all the required objects should be in the same frame. In this paper, we focus on concept alignment. As controllable T2I models have achieved satisfactory performance for real applications, we utilize this technology to replace the objects in a synthesized image in latent space step-by-step to change the image from a common scene to a counterfactual scene to meet the prompt. We propose a strategy to instruct this replacing process, which is called as Explicit Logical Narrative Prompt (ELNP), by using the newly SoTA language model DeepSeek to generate the instructions. Furthermore, to evaluate models' performance in counterfactual T2I, we design a metric to calculate how many required concepts in the prompt can be covered averagely in the synthesized images. The extensive experiments and qualitative comparisons demonstrate that our strategy can boost the concept alignment in counterfactual T2I.

[Arxiv](https://arxiv.org/abs/2505.14341)