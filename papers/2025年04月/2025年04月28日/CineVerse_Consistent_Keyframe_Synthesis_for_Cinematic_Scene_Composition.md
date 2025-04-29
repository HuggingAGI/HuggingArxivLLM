# CineVerse：电影场景的一致关键帧合成

发布时间：2025年04月28日

`LLM应用` `生成技术`

> CineVerse: Consistent Keyframe Synthesis for Cinematic Scene Composition

# 摘要

> 我们推出CineVerse——一个全新的电影场景合成框架。与传统多镜头生成类似，我们不仅追求帧间的一致性和连贯性，更专注于解决电影制作中的核心挑战，如多角色互动、复杂情节以及视觉效果呈现。为实现这一目标，我们首先构建了CineVerse数据集，并基于此数据集训练了创新的两阶段方法。首先，通过向大型语言模型（LLM）输入特定任务指令，使其能够从高层次场景描述中生成详细的场景规划，包括环境设定、角色安排及镜头设计。随后，我们对文本到图像生成模型进行微调，以合成高质量的视觉关键帧。实验结果表明，CineVerse在生成视觉连贯且内容丰富的电影场景方面表现优异，为未来电影视频合成技术的进一步探索奠定了坚实基础。

> We present CineVerse, a novel framework for the task of cinematic scene composition. Similar to traditional multi-shot generation, our task emphasizes the need for consistency and continuity across frames. However, our task also focuses on addressing challenges inherent to filmmaking, such as multiple characters, complex interactions, and visual cinematic effects. In order to learn to generate such content, we first create the CineVerse dataset. We use this dataset to train our proposed two-stage approach. First, we prompt a large language model (LLM) with task-specific instructions to take in a high-level scene description and generate a detailed plan for the overall setting and characters, as well as the individual shots. Then, we fine-tune a text-to-image generation model to synthesize high-quality visual keyframes. Experimental results demonstrate that CineVerse yields promising improvements in generating visually coherent and contextually rich movie scenes, paving the way for further exploration in cinematic video synthesis.

[Arxiv](https://arxiv.org/abs/2504.19894)