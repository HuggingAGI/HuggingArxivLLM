# CineTechBench：电影技术理解和生成的基准测试

发布时间：2025年05月21日

`LLM应用` `电影制作` `电影摄影`

> CineTechBench: A Benchmark for Cinematographic Technique Understanding and Generation

# 摘要

> 电影摄影学是电影制作与欣赏的基石，通过镜头运动、构图和 lighting 等视觉元素塑造氛围、情感和叙事。尽管多模态大型语言模型（MLLMs）和视频生成模型近期取得了进展，但现有模型理解和再现电影摄影技术的能力仍未得到充分探索，这主要受限于专家标注数据的稀缺性。为填补这一空白，我们推出 CineTechBench——首个基于资深电影摄影专家在关键维度上进行精准手动标注的基准测试。我们的基准涵盖七个核心要素：镜头尺度、镜头角度、构图、镜头运动、照明、色彩和焦距，并包含超过 600 张标注的电影图像和 120 个带有明确电影摄影技巧的电影片段。针对理解任务，我们设计了问答对和标注描述来评估 MLLMs 解释和阐述电影摄影技巧的能力。在生成任务中，我们评估先进视频生成模型在给定文本提示或关键帧等条件下重构电影级镜头运动的能力。我们对 15+ MLLMs 和 5+ 视频生成模型进行了大规模评估。我们的研究结果揭示了现有模型的局限性，并为自动电影制作与欣赏中的电影摄影理解与生成提供了未来方向。代码与基准测试可访问 https://github.com/PRIS-CV/CineTechBench。

> Cinematography is a cornerstone of film production and appreciation, shaping mood, emotion, and narrative through visual elements such as camera movement, shot composition, and lighting. Despite recent progress in multimodal large language models (MLLMs) and video generation models, the capacity of current models to grasp and reproduce cinematographic techniques remains largely uncharted, hindered by the scarcity of expert-annotated data. To bridge this gap, we present CineTechBench, a pioneering benchmark founded on precise, manual annotation by seasoned cinematography experts across key cinematography dimensions. Our benchmark covers seven essential aspects-shot scale, shot angle, composition, camera movement, lighting, color, and focal length-and includes over 600 annotated movie images and 120 movie clips with clear cinematographic techniques. For the understanding task, we design question answer pairs and annotated descriptions to assess MLLMs' ability to interpret and explain cinematographic techniques. For the generation task, we assess advanced video generation models on their capacity to reconstruct cinema-quality camera movements given conditions such as textual prompts or keyframes. We conduct a large-scale evaluation on 15+ MLLMs and 5+ video generation models. Our results offer insights into the limitations of current models and future directions for cinematography understanding and generation in automatically film production and appreciation. The code and benchmark can be accessed at https://github.com/PRIS-CV/CineTechBench.

[Arxiv](https://arxiv.org/abs/2505.15145)